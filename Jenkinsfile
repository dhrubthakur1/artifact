pipeline {
  agent any
  stages {
    stage ('Archive Artifacts') {
      steps {
        archiveArtifacts artifacts: 'README.md', fingerprint: true
        cleanWs()
      }
    }
  }
}
