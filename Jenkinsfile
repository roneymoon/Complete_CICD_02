pipeline {
	agent any

	tools {
		nodejs 'NodeJS'
	}
    
    	stages {
        	stage('Github') {
			steps {
                		git branch: 'main', credentialsId: 'jen-git-dind', url: 'https://github.com/roneymoon/Complete_CICD_02.git'
            		}
        	}
		stage('Unit Test') {
			steps {
				sh 'npm test'
				sh 'npm install'
			}
		}
    	}
}
