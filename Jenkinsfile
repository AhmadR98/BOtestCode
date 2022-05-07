pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
      }
    }
    stage('Test Stages') {
      parallel {
        stage('Test1') {
          steps {
            echo 'Test1 completed'
          }
        }

        stage('Test2') {
          steps {
            echo 'Test2 completed'
          }
        }

        stage('Test3') {
          steps {
            echo 'Test3 completed'
          }
        }

      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy Completed'
      }
    }

  }
}