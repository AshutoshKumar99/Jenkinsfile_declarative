pipeline {
  agent {
    label 'flower'
  }
    stages {
        
		
		stage('Build step') { 
            steps {
                
				withMaven(jdk: 'JDK8', maven: 'M2') {
              bat 'mvn clean install'
            }
				
				
            }
        }
        
		
		
        
    }
}