pipeline {
	agent any
	stages {
		stage('One') {
			steps {
				echo 'Hi, this is Soumitra from roytuts'
			}
		}
		
		stage('Build') {
            steps {
                bat './gradlew build'
            }
        }
        
        stage('Test') {
            steps {
                bat './gradlew test'
            }
        }
        
        stage('Check') {
            steps {
                bat './gradlew check'
            }
        }      
		
		stage('Five') {
			steps {
				echo 'Finished'
			}
		}		
	}
}
