pipeline {
  agent any
  stages {
    stage ('scm') {
      steps {
        git 'https://github.com/1234shaik/spring-framework-petclinic.git'
      }
    }
    stage ('mcn build') {
      steps {
        bat 'mvn clean test'
      }
    }
  }
}
