pipeline {

    agent any
    tools {
        maven 'Maven 3.5.0'
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

          stage('mvn install stage') {
              steps {
                sh "mvn install"
        }
    }

  }

}
