pipeline {
    agent any

    stages {
    
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
