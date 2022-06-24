pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh "/code/allen/new-icu/build/build_dashboard_manager.sh"'
      }
    }

  }
}