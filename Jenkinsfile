pipeline {
	agent none
    stages {
        stage('pull') {
		     steps { 
		                checkout scm	 
			 }
		}
		stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }
        
    }
}
