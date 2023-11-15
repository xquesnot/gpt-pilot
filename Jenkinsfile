pipeline {
  agent any
  stages {
    stage('Tests') {
      steps {
        echo 'démarrage du stage test'
        sleep 30
        echo 'Fin du stage test'
      }
    }

    stage('Build') {
      steps {
        echo 'Start build stage'
        sleep 20
        echo 'End build stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Start deploy stage'
        sleep 20
        echo 'End deploy stage'
      }
    }

  }
}