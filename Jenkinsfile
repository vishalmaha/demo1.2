pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'This is the $BUILD_NUMBER of  DEMO'
        sh 'echo "This is a build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}