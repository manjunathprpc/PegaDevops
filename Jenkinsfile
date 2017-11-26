pipeline {
  agent any
  stages {
    stage('Export From Dev') {
      steps {
        build 'ExportFromDev'
      }
    }
    stage('') {
      steps {
        build 'MoveToSharedSystem'
      }
    }
  }
}