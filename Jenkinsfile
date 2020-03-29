pipeline {
    agent any

    stages {
       
       
        stage('Build') {
            steps {
                sh "g++ main.cpp -o res.out "
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
