pipeline {
  agent any
  stages {
    stage('gitcheckout') {
      steps {
        git(url: 'https://github.com/elumalaiganesan/maven.git', branch: 'main', credentialsId: 'elumalaiganesan')
      }
    }

  }
}