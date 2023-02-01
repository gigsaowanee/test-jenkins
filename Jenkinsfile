pipeline {
    agent any

    stages {
       stage('Integration') {
   junit 'report.xml'
}

junit 'report.xml'

stage('Ignored') {
  withChecks('Integration Tests') {
    junit 'report.xml'
  }
}
    }
}