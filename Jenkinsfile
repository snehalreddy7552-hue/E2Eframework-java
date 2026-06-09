pipeline{
	agent any
	stages{
		stage('Checkout'){
			steps{
				echo 'Getting Project from github'
			}
		}
		stage('Build'){
			steps{
				bat 'mvn clean'
			}
		}
		stage('Execute Tests'){
			steps{
				bat 'mvn test'
			}
		}
		stage('Generate Reporters'){
			steps{
				echo 'reports genmerated successfully'
			}
		}
	}
}