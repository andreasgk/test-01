pipeline {
  agent any
  stages {
    stage('My Stage') {
      parallel {
        stage('My Stage') {
          steps {
            sh '''echo
'''
            timestamps()
          }
        }
        stage('') {
          steps {
            sh 'pwd'
          }
        }
      }
    }
    stage('Your Stage') {
      steps {
        echo 'hello world!'
        echo 'it\'s time to go to bed!'
      }
    }
  }
}