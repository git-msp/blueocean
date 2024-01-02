pipeline {
  agent any
  stages {
    stage('Checkout') {
      parallel {
        stage('Checkout') {
          steps {
            echo 'Checkout repo'
          }
        }

        stage('echo') {
          steps {
            sh '''#!/bin/bash

echo "Hello This is first step towards the moon"'''
          }
        }

      }
    }

  }
}