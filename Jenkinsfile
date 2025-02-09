// pipeline {
//     agent any
//     stage{
//         stage('Build'){
//             steps{
//                 print "Hello Jenkins"
//             }
//         }
//     }
// }
pipeline {
    agent any
    stages {  // ✅ ต้องมี "stages"
        stage('Build') {  // ✅ stages ต้องมี stage ข้างใน
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
