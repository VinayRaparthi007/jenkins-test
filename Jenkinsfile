pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/VinayRaparthi007/jenkins-test', branch: 'master')
      }
    }

    stage('shell') {
      steps {
        sh 'ls -l'
      }
    }

  }
}