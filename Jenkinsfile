pipeline {
    agent any
    tools {
        nodejs 'nodejs'
    }
       
    stage('Build') {
            steps {
                sh 'npm install'
                // sh 'npm run build'
            }
        }
        stage('Test') {
            steps {
                // sh 'npm run test'
                echo "Test"

            }
        }   
     }
