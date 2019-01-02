pipeline {
  agent any
  stages {
    stage('Sonar') {
      steps {
        withSonarQubeEnv 'Sonar'
      }
    }
  }
}