pipeline {
  agent any
  stages {
    stage('check') {
      steps {
        git(url: 'git@github.com:joeko0221/SpringcloudConfig.git', branch: 'master', credentialsId: 'dd')
      }
    }

    stage('test') {
      steps {
        sh 'ddds'
      }
    }

  }
}