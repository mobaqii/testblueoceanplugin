pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build complete'
      }
    }

    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo 'testing test1'
          }
        }

        stage('Testing phase2') {
          steps {
            echo 'test phase 2 complete'
          }
        }

        stage('Test phase 3') {
          steps {
            echo 'successfully '
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'deployment done'
      }
    }

  }
}