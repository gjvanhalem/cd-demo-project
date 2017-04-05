pipeline {
  agent any
  stages {
    stage('bogus stage') {
      steps {
        sh 'ls -sla'
        echo 'did an awesome ls'
      }
    }
    stage('Main stage') {
      steps {
        sleep 5
      }
    }
  }
}