pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hel 1234'
      }
    }
  }
   post {
        success {
            mail to:"xuanhieu1989@gmail.com", subject:"SUCCESS: ${currentBuild.fullDisplayName}", body: "Yay, we passed."
        }
        failure {
            mail to:"xuanhieu1989@gmail.com", subject:"FAILURE: ${currentBuild.fullDisplayName}", body: "Boo, we failed."
        }
    } 
}
