pipeline {
	agent any
	stages {
		stage('Upload to AWS'){
			steps {
				withAWS(
					region:'eu-west-1',
					credentials:'AKIA5XD7YZOQHMFB7HJO'
					)
				s3Upload(file:'index.html', bucket:'adri-jenkins-static')
			}
		}
	}
}