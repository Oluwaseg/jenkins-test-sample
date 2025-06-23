pipeline {
  agent any

  tools {
    nodejs 'NodeJS_24.2.0' 
  }

  stages {
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }

    stage('Run tests') {
      steps {
        sh 'npm test'
      }
    }
  }
}
