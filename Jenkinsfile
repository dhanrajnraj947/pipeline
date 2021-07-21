pipeline {
	agent any
	stages {
		stage('build') {
			when {
				branch 'main'
			}	
			steps {
				echo "BUILD IS RUNNING ......."
				sh 'sleep 5'
			}		
		}
	}	
}
