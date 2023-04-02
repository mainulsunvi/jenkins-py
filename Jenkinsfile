pipeline {
<<<<<<< HEAD
	agent { 
		node {
			label 'docker-agent-python3'
			}
	  }
=======
	agent {
		label 'docker-agent-python'
	}
	
>>>>>>> d11c6b611aad57b0d5db995350f5ff4666d50eef
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
				echo "doing delivery stuff.."
				
				'''
			}
		}
	}
}
