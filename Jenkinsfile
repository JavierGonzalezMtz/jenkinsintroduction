pipeline{
	agent any
	stages{
		stage('Preparing'){
			steps {
				echo "I'm in stage Preparing!"
				deleteDir()
				checkout scm
				echo "Finished getting files from github repository"
			}
		}
		stage('Build'){
			steps {
				echo "I'm in stage Build!"
				echo "Finished building"
			}
		}
		stage('Testing'){
			steps {
				echo "I'm in stage Preparing!"
				echo "Finished testing"
			}
		}
		stage('Deploying'){
			steps {
				echo "I'm in stage Preparing!"
				echo "Finished Deploying!"
			}
		}
		stage('NewStage!'){
			steps {
				echo "I'm in staeg only for branch2!!"
			}
		}
	}
}