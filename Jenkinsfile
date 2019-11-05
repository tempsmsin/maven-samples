pipeline {

    agent any
    tools {
        jdk 'java8'
        maven 'Maven3' 
    }
    stages {
        stage('Compile stage') {
            steps {
                sh "echo $JAVA_HOME"
                sh " mvn -version"
                
        }
    }

         

          

  }

}
