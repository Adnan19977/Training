pipeline {
    agent any
    	stages{
			stage('one'){
				steps{
					echo 'Hi, This is Adnan'
				}
			}
			stage('two'){
				steps{
					input('Do you want to proceed?')
				}
			}
			stage('Three'){
				steps{
					echo 'Testing Now'
				}
			}
			stage ('four'){
				parallel{
					stage('unit test'){
						steps{
							echo "Running the unit test"
						}
					}
					stage('integration test'){
						steps{
							echo ' Running the integration test .. '
						}
					}
				}
			}
		}
}