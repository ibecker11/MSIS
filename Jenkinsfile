pipeline {
  agent any
  stages {
    stage('Backup PROD') {
      steps {
        sh 'echo "testing"'
      }
    }

    stage('Restore') {
      parallel {
        stage('Restore') {
          steps {
            sh '''echo "testing 123"

'''
          }
        }

        stage('clone tree') {
          steps {
            sh 'echo "Clone code-tree"'
          }
        }

      }
    }

  }
}