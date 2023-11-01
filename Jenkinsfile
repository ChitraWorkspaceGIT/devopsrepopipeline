pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'I have a plan to work on CICD'
      }
    }

    stage('code') {
      steps {
        echo 'I have a development code to work on CICD'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'i have a build to work on CICD'
          }
        }

        stage('Test') {
          steps {
            echo 'I have a test to work on CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'i have a release to work on CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'i have to deploy to work on CICD'
          }
        }

        stage('Operate') {
          steps {
            echo 'i have operate to work on CICD'
          }
        }

      }
    }

  }
}