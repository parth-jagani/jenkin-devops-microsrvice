pipeline {
	agent any
	envrironment {
		dockerHome = tool 'myDocker'
		mavenHome = tool 'myMaven'
		PATH = "$dockerHome/bin:$mavenHome/bin:$PATH"
	}
	stages{
		stage('Build') {
			steps{
				sh 'docker version'
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
