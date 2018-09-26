pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "this is a build stage " '
            echo 'this is a first build stage'
          }
        }
        stage('build 2') {
          steps {
            sh 'echo "this is a build stage " '
          }
        }
      }
    }
  }
}