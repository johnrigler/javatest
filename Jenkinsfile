pipeline {
  agent any
  stages {
  stage('Compile') {
      steps {
        script {
          sh 'javac HelloWorld.java
        }
      }
    }
  stage('Test') {
      steps {
        script {
          sh 'java HelloWorld' 
        }
      }
    }
  }
}
