pipeline {
    agent any
    stages {  
        stage('Check Out') { 
            steps {
                print 'Check Out'
                checkout([
                $class: 'GitSCM', 
                branches: [[name: '*/main']], 
                userRemoteConfigs: [ [ 
                credentialsId: '1234', 
                url: "https://github.com/Khanchai-pat/multiplication-table.git "
                ] ]
                ])
            }
        }
        stage('Build') { 
            steps {
                print 'Building and Deploying'
            }
        }
        stage('test') {
            steps {
                print 'Testing'
            }
        }
    }
}
