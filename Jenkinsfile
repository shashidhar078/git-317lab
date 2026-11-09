pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac src/Main.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java -cp src Main'
            }
        }
    }
}
