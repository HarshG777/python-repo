pipeline {
    agent { label 'agent1' }
 
    stages {
        stage('Compile') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Run') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
