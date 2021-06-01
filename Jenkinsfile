pipeline {
    agent none
    stages {
        stage ('Hello') {
            agent any
            steps {
                echo 'Hello, '
                sh '''#!/bin/bash
                    pwd
                    wget http://18.236.95.14:8080/jnlpJars/jenkins-cli.jar
                    ls -l
                    java -jar ./jenkins-cli.jar -s http://18.236.95.14:8080 groovy user-creation.groovy testUser testPassword testEmail@testEmail.com
                '''
            }
        }
    }
}
