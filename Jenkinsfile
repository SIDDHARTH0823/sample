pipeline {
  agent any
  stages {
    stage('main') {
      steps {
        sh 'echo "This is main branch.."'
      }
    }

    stage('dev') {
      steps {
        sh 'echo "This is dev branch..-new"'
      }
    }

    stage('hotfix') {
      steps {
        sh 'echo "This is hotfix branch"'
      }
    }
  }
}
