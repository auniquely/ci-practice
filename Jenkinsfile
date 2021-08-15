pipeline {
    agent any

	tools{
	go '1.16.7'
	}


    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh 'go build main.go'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }


    post{
	always {
		echo 'Pipeline Complete'


	}


    }

}
