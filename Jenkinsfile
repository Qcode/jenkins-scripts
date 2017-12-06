pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building dependencies...'
        sh 'printenv'
        sh 'exit 1'
        /*sh 'rm -rf node_modules/'
        sh 'yarn install --mutex network'*/
      }
      post {
        failure {
          echo 'This is failure thing'
          sh 'printenv'
        }
      }
    }

    /*stage('Lint') {
      steps {
        echo 'Linting...'
        sh 'yarn lint'
      }
    }

    stage('Unit Tests') {
      steps {
        echo 'Running unit tests...'
        withEnv(['CI=true']) {
          sh 'yarn test'
        }
      }
    }*/
  }
}
