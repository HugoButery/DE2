pipeline {
  agent any
  stages {
    stage('build') {
      steps{
          bat 'docker build . -t de'
      }
    }
    stage('run'){
      steps {
          bat 'docker run -p 3000:3000 de'
      }
    }
  }
}