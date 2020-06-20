pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './gradlew build'
      }
    }

    stage('Test') {
      steps {
        sh 'ls'
      }
    }

    stage('Analyze') {
      steps {
        sh 'true'
      }
    }

    stage('Validate') {
      steps {
        sh 'true'
      }
    }

    stage('Deploy') {
      steps {
        sh 'true'
      }
    }

  }
}
