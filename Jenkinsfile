pipeline {
	agent {docker {image 'node:13.8'}}
	stages{
		stage('Build') {
			steps{
				sh 'node --version'
				echo "Build"
			}
			
		}
		stage('Test') {
			steps{
				echo "Test"
			}
			
		}
		stage('Int Test') {
			steps{
				echo "Int Test"
			}
			
		}
	
	} 
	
}
