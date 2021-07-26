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

    stage('xxxxxxxxxxxxx') {
      parallel {
        stage('xxxxxxxxxxxxx') {
          steps {
            build(job: 'maven build', wait: true, quietPeriod: 2)
          }
        }

        stage('') {
          steps {
            error 'asd'
          }
        }

      }
    }

    stage('') {
      steps {
        sleep 1
      }
    }

  }
}