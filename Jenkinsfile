pipeline {
    agent any
  stages {
    stage('Config list'){
      steps {
        sh 'npm config ls'
        sh 'node -v'
        sh 'npm -v'
        
      }
    }
    stage('Install'){
      steps{
        sh 'npm install'
        echo ("NPM installing")
      }
    }
    stage('Run'){
      steps{
        sh 'npm run'
        echo ('Running the application')
      }
    }
    stage ('Test') {
      steps {
        sh 'npm test'
        echo ('Testing the application')
      }
    }
  }
}
