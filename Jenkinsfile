
pipeline {
    agent none
    stages {
        stage('test') {
             agent { label 'linux' }
             steps {
                 sh 'echo hello world'
             }
        }
     }
}
