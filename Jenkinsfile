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
			stage('Four'){
				steps{
					echo 'Testing Now'
					dir("com.example.test") {
						bat 'mvn test'
					}
				}
			}
		}
}