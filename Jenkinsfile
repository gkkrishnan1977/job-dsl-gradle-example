pipeline {
  agent none
  stages {
    stage('DevStage') {
      steps {
        sh 'Echo "DevStage"'
      }
    }
  }
  environment {
    Dev = '192.168.42.129'
    test = '192.168.42.129'
  }
}