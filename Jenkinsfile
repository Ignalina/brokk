pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'podman build -f Dockerfile.rhel7 .'
      }
    }

  }
}