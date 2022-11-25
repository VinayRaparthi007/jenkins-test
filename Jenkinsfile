pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        sh 'la -l'
        git(url: 'https://github.com/VinayRaparthi007/jenkins-test', branch: 'master')
      }
    }

  }
}