pipeline {

    agent any
    tools {
        java 'java8'
        maven 'Maven3' 
    }
    stages {
        stage('Compile stage') {
            steps {
                sh "mvn clean compile" 
        }
    }

         stage('testing stage') {
             steps {
                sh "mvn test"
        }
    }

          stage('deployment stage') {
              steps {
                sh "mvn deploy"
        }
    }

  }

}
