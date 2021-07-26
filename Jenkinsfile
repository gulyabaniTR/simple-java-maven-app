pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'sa'
          }
        }

        stage('asddddddddd') {
          steps {
            sleep 2
          }
        }

        stage('asdasdasd') {
          steps {
            sh '''#!/bin/sh
# This is a comment!
echo Hello World        # This is a comment, too!'''
          }
        }

      }
    }

    stage('error') {
      steps {
        sh '''#!/bin/sh
# This is a comment!
echo HURRRRAAAY  # This is a comment, too!'''
      }
    }

    stage('delay') {
      steps {
        sleep 1
      }
    }

    stage('çükübik') {
      steps {
        sh 'maven build'
      }
    }

    stage('wolololo') {
      steps {
        echo 'HURRRRRRRRRRA'
      }
    }

  }
}