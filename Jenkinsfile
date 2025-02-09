pipeline {
    agent any
    stages {  
        stage('git') { 
            steps {
                print 'git push'
            }
        }
        stage('Build') { 
            steps {
                print 'Building'
            }
        }
        stage('Deploy') {
            steps {
                print 'Deploying' 
            }
        }
        stage('test') {
            steps {
                print 'Testing'
            }
        }
    }
}
