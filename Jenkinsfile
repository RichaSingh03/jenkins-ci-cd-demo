pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/RichaSingh03/jenkins-ci-cd-demo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac src/main/java/HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java -cp src/main/java HelloWorld'
            }
        }
        stage('Test') {
            steps {
                echo 'No tests yet!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
