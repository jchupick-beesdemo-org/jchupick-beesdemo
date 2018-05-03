pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('Version Dump') {
      steps {
        sh 'java -version'
      }
    }
  }
}