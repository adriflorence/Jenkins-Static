pipeline {
	agent any
	stages {
		stage('Build'){
			steps {
				sh 'echo "Hi World"'
				sh '''
					echo "Multi-line shell steps yay"
					ls -lah
					'''
			}
		}
	}
}