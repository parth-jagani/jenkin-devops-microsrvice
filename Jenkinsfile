pipeline {
	agent {docker {image :'maven:3.8.1'}}
	stages{
		stage('Build') {
			steps{
				sh 'mvn --version'
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
