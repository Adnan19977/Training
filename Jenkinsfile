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
			when {
				not { branch "master" }
			}steps{
				echo " This is not master branch " )
							
				}
			}
		}
}