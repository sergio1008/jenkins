pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }
        stage('deploy'){
            steps {
            	sh 'java -jar   ./target/*.jar'
            }	
        }
    }
}
