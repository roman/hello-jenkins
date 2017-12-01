pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        node(label: 'foobar') {
          error 'Go to hell'
        }
        
      }
    }
    stage('Build') {
      steps {
        sh 'echo "building"'
      }
    }
  }
}