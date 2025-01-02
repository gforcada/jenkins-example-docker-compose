pipeline {
  agent any
  stages {
    stage("verify tooling") {
      steps {
        sh '''
          curl --version
        '''
      }
    }
  }
}
