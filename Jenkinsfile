pipeline {
  agent any
  stages {
    stage("verify tooling") {
      steps {
        sh '''
          curl --version
          docker version
          docker info
          docker compose version 
        '''
      }
    }
  }
}
