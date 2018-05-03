pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello World ${MY_NAME}!"
      }
    }
    stage('Version Dump') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'JBC'
  }
}