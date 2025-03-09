pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		bat 'mvn clean'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		bat 'mvn testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		bat 'mvn deploy'
            }
        }
stage('Release') {
            steps {
                echo 'Release....'
		
            }
        }


    }
}
