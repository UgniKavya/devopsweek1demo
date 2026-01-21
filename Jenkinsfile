pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git 'https://github.com/UgniKavya/devopsweek1demo.git'
            }
        }
        stage('compile')
        {
            steps
            {
                sh 'javac hello1.java'
            }
        }
        stage('run')
        {
            steps
            {
                sh 'java hello1'
            }
        }
    }
}
