pipeline {
  agent any
  stages {
    stage('Paso 1') {
      steps {
        withSonarQubeEnv('SonarPrep') {
          withSonarQubeEnv 'Sonar'
        }

      }
    }
    stage('Paso 2') {
      steps {
        waitForQualityGate true
      }
    }
  }
}