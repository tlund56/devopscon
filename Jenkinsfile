pipeline {
  agent {
    docker {
      image 'maven:3.5.3-jdk-8'
    }

  }
  stages {
    stage('Compile') {
      steps {
        sh 'mvn compile'
      }
    }
    stage('') {
      steps {
        sh 'mvn install'
      }
    }
  }
}