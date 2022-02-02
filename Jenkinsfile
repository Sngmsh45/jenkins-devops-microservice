pipeline {
	    agent any

		environment{
			dockerHome=tool 'myDocker'
			mavenHome=tool 'myMaven'
			PATH = "$dockerHome/bin:$mavenHome/bin:$PATH"
		}
		stages {

			stage('Build'){

				steps{
					sh 'mvn --version'
					sh  'docker version'
			
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
