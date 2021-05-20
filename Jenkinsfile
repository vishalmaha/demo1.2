pipeline {
  agent any
  stages {
    stage('Stage1') {
      agent any
      environment {
        DEMO = '1'
      }
      steps {
        sh 'echo "This is a build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}