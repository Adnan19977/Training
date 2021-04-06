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
					input(' Do you want to proceed?')
				}
			}
		}
}