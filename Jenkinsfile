pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('Greet') {
          steps {
            echo 'Hello there.!'
            sh 'echo "How are you?"'
          }
        }

        stage('Thank you') {
          steps {
            echo 'Thank you for using jenkins pipelines'
          }
        }

      }
    }

  }
}