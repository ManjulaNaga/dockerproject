pipeline {
    agent any 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
            }
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
