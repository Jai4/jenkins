@Library('jenkins-sharedlib')_

pipeline {
    agent any
    stages { 
        stage('one') {
            steps {
                hello 'Hello World'
            }
        }
         stage('second') {
            steps {
                echo 'i am getting executed'
            }
        }
    }
}
