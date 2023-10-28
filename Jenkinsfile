pipeline {
  agent any
  stages {
    stage('Plan') {
      parallel {
        stage('Plan') {
          steps {
            echo 'Plan stage'
          }
        }

        stage('Code') {
          steps {
            echo 'Code stage'
          }
        }

        stage('Build') {
          steps {
            echo 'Build Stage'
          }
        }

      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Test Stage'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deploy stage'
          }
        }

      }
    }

    stage('Release') {
      steps {
        echo 'Release stage'
      }
    }

    stage('Production') {
      steps {
        echo 'Production Stage'
      }
    }

    stage('operate') {
      steps {
        echo 'operate stage'
      }
    }

  }
}