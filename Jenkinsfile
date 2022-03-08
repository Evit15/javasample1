pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello 1234'
      }
    }
    stage('build job') {
      steps {
        build 'job1'
      }
    }
  }
}
