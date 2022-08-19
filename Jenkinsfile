pipeline {
  agent any
  stages {
    stage('prueba') {
      parallel {
        stage('prueba') {
          steps {
            echo 'asddasasdasasd'
          }
        }

        stage('sleep') {
          steps {
            sleep 5
          }
        }

        stage('prueba 3') {
          steps {
            echo 'prueba'
          }
        }

      }
    }

  }
}