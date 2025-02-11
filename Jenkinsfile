pipeline {
    agent { label 'java_agent' }
 
    stages {
        stage('Compile') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Run') {
            steps {
                sh 'hello.py'
            }
        }
    }
}
