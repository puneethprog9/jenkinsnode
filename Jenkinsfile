pipeline {
    agent {
	    node{
		   label 'redhat'
		}
	}

    stages {
        stage('Build') {
            steps {
                checkout scm
		    
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
