pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        echo 'import from CR'
      }
    }
    stage('execute ') {
      steps {
        echo 'job exec'
      }
    }
    stage('deploy') {
      agent any
      steps {
        echo 'deploy'
      }
    }
  }
  environment {
    dev = ''
  }
}