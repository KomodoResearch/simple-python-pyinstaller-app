pipeline {
    agent none
    stages {
        stage ('Hello') {
            agent any
            steps {
                echo 'Hello, '
                sh '''#!/bin/bash
                    wget http://18.236.95.14:8080/jnlpJars/jenkins-cli.jar
                    java -jar ./jenkins-cli.jar -s http://http://18.236.95.14:8080 groovy user-creation.groovy testUser testPassword testEmail@testEmail.com
                '''
            }
        }
    }
}
