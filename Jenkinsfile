pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building dependencies...'
        sh 'printenv'
        /*sh 'rm -rf node_modules/'
        sh 'yarn install --mutex network'*/
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
