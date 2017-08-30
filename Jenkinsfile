pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/PrabhakaranAnnadurai/DemoProject1', branch: 'master')
        archiveArtifacts 'test.txt'
      }
    }
  }
}