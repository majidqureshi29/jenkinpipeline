pipeline {
  agent any

  environment {
    DEV_SSH_CRED = 'dev-ssh-key'   // Jenkins credential ID for dev
    BUILD_ARTIFACT = 'dist.zip'
  }

  stages {
    stage('Pull code') {
      steps {
        echo "Pulling code"
      }
    }
  }
}