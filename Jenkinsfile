pipeline {
	agent any
	tools {
		go '1.16.7'

	}
	stages {
		stage('build'){
			echo 'Step 1'
			sh 'go build main.go'
		}
		stage('test'){
			echo 'Sample Test'

		}
		stage('package'){
			echo 'Package binary'
		}
}
	post{
		always{
			echo 'Pipeline has completed'
		}
	

	}


}


