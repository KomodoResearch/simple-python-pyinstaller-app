pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        echo 'Hello, '
        sh '''#!/bin/bash
sudo useradd pawnd    '''
      }
    }

  }
}