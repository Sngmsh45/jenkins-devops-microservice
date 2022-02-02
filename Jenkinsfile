pipeline {
	    agent {docker {image 'node:17.4'}}
		stages {

			stage('Build'){

				steps{
				sh 'node --version'
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
