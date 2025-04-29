pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/RiddhiUnawane0902/html3.git'
            }
        }

        stage('Deploy') {
            steps {
                script {
                    bat 'copy file1.html C:\\xampp\\htdocs\\file1.html'
                }
            }
        }
    }
}
