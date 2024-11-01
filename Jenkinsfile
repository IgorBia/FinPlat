pipeline {
    agent any
    stages {
	stage('Install Maven') {
	    steps {
		sh 'apt-get install maven'
            }
	}
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

