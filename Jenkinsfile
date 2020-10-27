@Library('jenkins-sharedlib')_

pipeline {
    agent any
    stages { 
        stage('one') {
            steps {
                sayHello 'Hello World'
            }
        }
         stage('second') {
            steps {
                echo 'i am getting executed'
            }
        }
    }
}
