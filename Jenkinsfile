pipeline {
	agent{
		node {
			label 'docker-agent-python'
		}
	}
	triggers {
		pollSCM '*/2 * * * *'
	}
	stages {
		stage('Build') {
			steps {
				echo "Building.."
				sh '''
				echo "doing build stuff.."
				
				'''
			}
		}
		stage('Test') {
			steps {
				echo "Testing.."
				sh '''
				echo "doing test stuff.."
				
				'''
			}
		}
		stage('Deliver') {
			steps {
				echo 'Deliver....'
				sh '''
				python3 hello.py
				
				'''
			}
		}
	}
}
