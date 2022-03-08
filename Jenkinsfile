pipeline {
  agent any
  parameters {
    string defaultValue: '123', name: 'param1', trim: true
  }
  stages {
    stage('build') {
      steps {
        echo "Hello ${params.param1}"
      }
    }
  }
}
