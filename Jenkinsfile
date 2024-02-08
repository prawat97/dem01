pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is $build_number of job $demo'
      }
    }

  }
  environment {
    demo = '1'
  }
}