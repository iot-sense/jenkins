pipeline {
  agent any
  stages {
    stage('build_dashboard_manager') {
      steps {
        sh 'sh "/code/dolly/icu-dashboard-dev/build/build_dashboard_manager.sh"'
      }
    }

  }
}