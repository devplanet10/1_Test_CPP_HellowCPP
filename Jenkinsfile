pipeline {
    agent any

    stages {
       
        stage('Chekcout') {
            steps {
                git checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                make
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
