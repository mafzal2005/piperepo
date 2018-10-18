pipeline {
  agent any
  stages {
    stage('First stage . which is build') {
      parallel {
        stage('second stage') {
          steps {
            sh 'echo "this is a build stage " '
            echo 'this is a first build stage'
          }
        }
        stage('third stage ') {
          steps {
            sh 'echo "this is a build stage " '
          }
        }
      }
    }
  }
}
