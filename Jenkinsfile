pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                sh 'python3 main.py'
                sh 'echo "jenkins script is working"'
            }
        }
    }
}