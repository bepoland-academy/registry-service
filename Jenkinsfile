pipeline {
  agent any
  stages {
    stage('Checkout Sources') {
      steps {
        git(url: ' https://github.com/bepoland-academy/registry-service.git', branch: 'development')
      }
    }
  }
}