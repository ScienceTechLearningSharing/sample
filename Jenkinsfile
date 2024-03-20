pipeline {
  agent {
    node {
      label 'test_node'
    }

  }
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/ScienceTechLearningSharing/speedr.git'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}