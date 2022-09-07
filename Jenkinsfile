pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'The Current Build number $BUILD_NUMBER of demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}