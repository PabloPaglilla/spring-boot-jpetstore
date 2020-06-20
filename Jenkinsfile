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
        sh './gradlew -Dsonarqube.host.url=http://sonarqube-grupo1:9000 sonarqube'
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