pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello-world'
        sh "mvn install"
      }
    }
    stage('deploy') {
      steps {
        echo 'I am in stage deploy'
      }
    }
  }
}
