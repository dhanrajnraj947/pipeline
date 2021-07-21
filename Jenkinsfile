pipeline {
	agent any
	stages {
		stage('STAGE1') {
			steps {
				catchError(buildResult: 'SUCCESS', stageResult: 'FAILURE') {
					echo "STAGE 1 IS RUNNING ......."
					sh 'sleep 5'
					sh 'exit 1'
				}	
			}	
		}
		
		stage('STAGE2') {
			steps {
				echo "STAGE 2 IS RUNNING ......."
				sh 'sleep 5'
				
			}	
		}
		
	}	

// This is a single line comment
		
/* This is multiple line comment 
	line 2
	line 3
	line 4
*/	
		
}
