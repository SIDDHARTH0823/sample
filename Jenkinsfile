pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'hi', quietPeriod: 3)
      }
    }

    stage('run') {
      steps {
        echo 'ok done'
      }
    }

  }
}