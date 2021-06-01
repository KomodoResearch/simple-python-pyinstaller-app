pipeline {
    agent none
    stages {
        stage ('Hello') {
            agent any
            steps {
                echo 'Hello, '
                sh '''#!/bin/bash
                    java -jar /home/ec2-user/jenkins-cli.jar -s http://http://18.236.95.14:8080 groovy user-creation.groovy testUser testPassword testEmail@testEmail.com
                '''
            }
        }
    }
}
