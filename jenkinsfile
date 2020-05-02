pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh 'tar czvf example2.tar.gz *.rb'
      }
    }
    stage('Publish') {
      steps {
        archiveArtifacts 'example2.tar.gz'
      }
    }
}
}
