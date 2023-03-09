pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'javac Hello.java'
      }
    }
    stage('hello') {
      steps {
        bat 'java HelloWorld'
      }
    }
  }
}
