pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
        stage('Example Test') {
    		when{
		     not{
			 branch "master"
			}
		}
		steps {
                	echo 'Hello, JDK'
            	}
        }
    }
}
