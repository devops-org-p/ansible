pipeline {
  agent any

  stages {
    stage("Setup"){
      steps {
        echo "Hello ansible"
        sh "date"
      }
    }
    stage("Configure"){
      steps {
        sh "cp Jenkinsfile test.text"
      }
    }
  }
}
