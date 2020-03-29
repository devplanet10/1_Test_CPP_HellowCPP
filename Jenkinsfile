pipeline {
    agent any

    stages {
       
       
        stage('Build') {
            steps {
                sh "gcc main.cpp -o res.out "
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
                sh "./res.out"
            }
        }
    }
}
