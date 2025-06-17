pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                sh 'python main.py'
                sh 'echo "jenkins script is working"'
            }
        }
    }
}