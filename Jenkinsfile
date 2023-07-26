pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git(branch: 'main', url: 'https://github.com/bakuvi95/calculator.git', changelog: true)
      }
    }

  }
}