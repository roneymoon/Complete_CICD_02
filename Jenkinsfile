pipeline {
	agent any	
	stages('Github') {
		steps {
			git branch: 'main', credentialsId: 'jen-git-dind', url: 'https://github.com/roneymoon/Complete_CICD_02.git'
		}
	}
}
