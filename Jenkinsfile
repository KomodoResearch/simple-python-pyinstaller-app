pipeline {
    agent none
    stages {
        stage ('Hello') {
            agent any
            steps {
                echo 'Hello, '
                sh '''#!/bin/bash
                    echo "Hack from bash" > /home/ec2-user/hack.txt
                    echo "Who I'm $SHELL"
                '''
            }
        }
    }
}
