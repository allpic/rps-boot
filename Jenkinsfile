pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Welcome toi'
          }
        }

        stage('demo') {
          steps {
            echo 'ca marche ? oui ou non ? que peut-on faire ?'
          }
        }

        stage('devel') {
          steps {
            sh 'ps au'
          }
        }

      }
    }

  }
}