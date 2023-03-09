pipeline {
    agent any
	stages {

    stage('Biuld') {
            steps {
                echo 'building...'
            }
        }
        
        stage('Test') {
            steps {
                echo 'testing...'
            }
        }
		
		stage('Pre-Deploy') {
            steps {
                echo 'Pre-Deploy...'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'deploying...'
            }
        }
    }
}
