pipeline {
	    agent any
		stages{
			stage('Build'){
				steps{
				echo"Build"
				

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
			
		}post{
			always{
				echo "im awesome i Run Always "
			}
			sucess{
				echo "i run oly when ur Sucessful "
			}
			failure{
				echo "I run When i Fail" 
			}
		}
		
	
	

}
