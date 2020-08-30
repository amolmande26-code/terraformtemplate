pipeline {
    agent any

 environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
 }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''#!/bin/bash/'''
				sh 'git add . '
				sh 'git commit -m "jenkins commit" '
				sh 'git push'
            }
        }
    }

}