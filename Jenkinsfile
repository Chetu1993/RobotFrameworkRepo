pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		bat 'mvn clean'
            }
        }

  stage('Deploy') {
            steps {
                echo 'Deploying....'
		bat 'mvn deploy'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing..'
		bat 'mvn test'
            }
        }
      
stage('Release') {
            steps {
                echo 'Release....'
		
            }
        }


    }
}
