pipeline {
    agent any

    stages {
      stage('Test'){
            steps{
                sh 'java -jar ../lib/junit-platform-console-standalone-1.7.0-all.jar -cp "."'
                junit '**/report.xml'
            }
        }

    }
}