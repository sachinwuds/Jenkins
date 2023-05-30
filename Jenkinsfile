pipeline {
    agent { docker { images python:3.10.7-alpine } }
    stages {
        stage( build ){
          steps {
            sh 'python --version'
          }
        }
    }
}
