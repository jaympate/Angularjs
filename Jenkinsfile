pipeline {
    agent any
  stages {
    stage('Config list'){
      steps {
        sh 'npm config ls'
        
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
        sh 'npm run test'
        echo ('Testing the application')
      }
    }
  }
}
