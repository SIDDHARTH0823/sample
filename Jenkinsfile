pipeline {
  agent any
  stages {
    stage('main') {
      steps {
        sh 'echo "This is main branch..-new"'
      }
    }

    stage('dev') {
      steps {
        sh 'echo "This is dev branch"'
      }
    }

    stage('hotfix') {
      steps {
        sh 'echo "This is hotfix branch"'
      }
    }
  }
}
