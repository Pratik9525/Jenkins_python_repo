pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'javac Main.java'
      }
    }
    stage('hello') {
      steps {
        bat 'java Main'
      }
    }
  }
}
