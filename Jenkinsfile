pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build Steps are getting executed....'
          }
        }

        stage('Build1') {
          steps {
            echo 'Build second part of the code....'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Let\'s deploy the code on testing servers... '
      }
    }

  }
}