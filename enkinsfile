pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               echo "Test successful"
              bat "mvn compile"
            }
        }
        stage('Deploy') {
            steps {
               echo "build successful"
              bat "mvn clean"
            }
        }
        stage('Test') {
            steps {
                echo "Test successful"
              bat "mvn test"
            }
        }
        
    }
}
