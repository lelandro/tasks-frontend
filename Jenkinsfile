pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -DskipTests=true clean package'
      }
    }

    stage('Unit Tests') {
      steps {
        sh 'mvn test'
      }
    }

  }
}