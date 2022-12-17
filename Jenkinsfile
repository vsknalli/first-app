

pipeline {
  agent any
  stages {
    stage('Stage 1-FETCH CODE FROM GIT') {
      steps {
        script {
          git 'https://github.com/vsknalli/first-app/'
        }

      }
    }

    stage('Compile MVN package') {
      steps {
         sh 'mvn package'        
      }
    }

    stage('Stage 3') {
      steps {
        script {
          echo 'Stage 3'
        }

      }
    }

    stage('Stage 4') {
      steps {
        script {
          echo 'Stage 4'
        }

      }
    }

  }
}
