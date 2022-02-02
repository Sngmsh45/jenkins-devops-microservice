pipeline {
	    agent {docker {image 'maven:3.6.3'}}
		stages {

			stage('Build'){

				steps{
				sh 'mvn --version'
				echo "Build"
				

				}
			}
				stage('Test'){

				steps{
				
				echo"Test"
				

				}
			}
				stage('Integration Test'){

				steps{
				
				echo"Integration Test"

				}
			}
			
		}
		post{
			always{
				echo "im awesome i Run Always "
			}
			success{
				echo "i run oly when ur Sucessful "
			}
			failure{
				echo "I run When i Fail" 
			}
		}
}
