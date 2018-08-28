pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${My_Name}!"
        sh 'java -version'
      }
    }
  }
}