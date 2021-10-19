pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        git(url: 'https://github.com/drajput2007/devops.git', branch: 'devops', changelog: true)
      }
    }

  }
}