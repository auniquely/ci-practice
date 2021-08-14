pipeline {
	agent any

	stages {
		stage('build'){
			echo 'Step 1'
			go build main.go
		}
		stage('test'){
			echo 'Sample Test'

		}
		stage('package'){
			echo 'Package binary'
		}

	post{
		always{
			echo 'Pipeline has completed'
		}
	

	}


	}


}
