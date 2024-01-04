pipeline {
  agent any
  stages {
    stage('Checkout') {
            steps {
                script {
                    // Checkout the code from the repository
                    checkout scm
                }
            }
    }
    stage("build") {
      steps {
        echo 'building the application...'
      }
    }
    stage("test"){
      steps{
        echo 'testing the application...'
      }
    }
    stage("deploy") {
      steps{
        echo 'deplying the application...'
      }
    }
  }
}
