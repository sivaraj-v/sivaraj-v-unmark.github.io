pipeline {
  agent any
  stages {
    stage('Develop') {
      parallel {
        stage('Develop') {
          steps {
            echo 'Develop'
          }
        }
        stage('Step') {
          steps {
            echo 'Step'
          }
        }
      }
    }
    stage('Qa') {
      steps {
        echo 'QA'
      }
    }
  }
}
