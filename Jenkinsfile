pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning the repository'
            }
        }
        stage('Build') {
            steps {
                echo 'No build needed for static site'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python -m http.server 8081 &'
                echo 'Deployed at http://localhost:8081'
            }
        }
    }
}
