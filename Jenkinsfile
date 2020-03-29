pipeline {
    agent any

    stages {
       
       
        stage('Build') {
            steps {
                sh "make all"
                echo 'Building..'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
