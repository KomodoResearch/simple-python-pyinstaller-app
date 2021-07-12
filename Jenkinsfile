pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        sh '''#!/bin/bash
        whoami
        '''
      }
    }

  }
}
