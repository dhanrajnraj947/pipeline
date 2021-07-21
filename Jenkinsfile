pipeline {
	agent any
	stages {
		stage('build') {
			when {
				branch 'master'
			}	
			steps {
				echo "BUILD IS RUNNING ......."
				sh 'sleep 5'
			}		
		}
	}	
}
