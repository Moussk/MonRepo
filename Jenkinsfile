pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            sh 'npm install'
          }
        }
        stage('') {
          steps {
            sleep 10
          }
        }
        stage('') {
          steps {
            echo 'hello mouss'
          }
        }
        stage('') {
          steps {
            emailext(subject: 'test blue ocean', body: 'Bonjour Mouss', from: 'babakanoute@gmail.com', to: 'moussa.kanoute.km@gmail.com')
          }
        }
      }
    }
  }
}