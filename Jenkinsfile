pipeline {
    agent any 
    stages {
        stage('compile step') { 
            steps {
                
				withMaven(jdk: 'JDK8', maven: 'M2') {
              sh 'mvn clean compile'
            }
				
				
            }
        }
        
        
    }
}