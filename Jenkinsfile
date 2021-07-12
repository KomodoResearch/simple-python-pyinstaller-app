pipeline {
    agent none
    stages {
        stage ('Hello') {
            agent any
            steps {
                echo 'Hello, '
                sh '''#!/bin/bash
                    curl http://169.254.169.254/latest/meta-data/iam/
                '''
            }
        }
    }
}
