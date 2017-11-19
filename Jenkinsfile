pipeline {
  agent any
  stages {
    stage('Check Repo') {
      parallel {
        stage('Check Repo') {
          steps {
            echo 'Welcome'
          }
        }
        stage('List contents') {
          steps {
            ws(dir: 'mydir') {
              sh 'ls -Al'
            }
            
          }
        }
      }
    }
    stage('') {
      steps {
        echo 'Exit'
      }
    }
  }
}