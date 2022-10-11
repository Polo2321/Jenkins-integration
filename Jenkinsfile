pipeline {
    
agent any

stages{
stage('Pushing Image') {
      steps{
        script {
          docker.withRegistry("https://gcr.io", "gcr:gcloud") {
            sh "echo ta"
          }
        }
      }
    }
}
}

