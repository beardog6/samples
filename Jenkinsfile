pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo hello'
            sh 'echo sssss'
          }
        }

        stage('') {
          steps {
            echo '222222'
          }
        }

      }
    }

    stage('') {
      steps {
        sleep 1
      }
    }

  }
}