pipeline {
  agent {
    label 'flower'
  }
    stages {
        stage('compile step') { 
            steps {
                
				withMaven(jdk: 'JDK8', maven: 'M2') {
              bat 'mvn clean compile'
            }
				
				
            }
        }
        
        
    }
}