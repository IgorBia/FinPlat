pipeline {
    agent any
    stages {
	stage('Install Maven') {
	    steps {
		sh 'sudo apt-get install maven'
            }
	}
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

