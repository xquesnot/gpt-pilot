pipeline {
  agent any
  stages {
    stage('Tests') {
      steps {
        git(url: 'https://github.com/xquesnot/gpt-pilot.git', branch: 'main')
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