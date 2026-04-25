pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    parameters {
        booleanParam(name: 'executeTests', defaultValue: true, description: 'Run tests?')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
