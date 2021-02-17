pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello, World!'
      }
    }
    stage('tacocat') {
      steps {
        sh 'cat tacocat'
      }
    }
    stage('tacocat backwards') {
      steps {
        sh 'cat tacocat-backwards'
      }
    }
  }
}
