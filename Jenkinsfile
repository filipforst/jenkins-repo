pipeline {
    agent { 
        node {
            label 'apache-template'
            }
      }
    stages {
        stage('Build') {
            steps {
                echo "Building.. 2222"
                sh '''
                echo "doing build stuff.."
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "doing test stuff.."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
