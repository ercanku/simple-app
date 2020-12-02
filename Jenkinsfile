pipeline {
    agent any
    tools {
        maven 'maven3'
      }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering...'
            }
        }
    }
}