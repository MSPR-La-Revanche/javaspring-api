pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Lancement des test...'
        sh 'mvn clean install -Dlicence.skip=true'
      }
    }

  }
  tools {
    maven 'Maven'
  }
}