/* pipeline {
  agent any
  /*tools {
    maven 'maven'
  }*/
  stages {
    stage ('scm') {
      steps {
        git 'https://github.com/1234shaik/spring-framework-petclinic.git'
      }
    }
    /* stage ('maven build') {
      steps {
        bat 'mvn clean compile'
      }
    } */
  }
} */

pipeline {
    agent any
    stages {
        stage ("scm") {
            steps {
                git ' https://github.com/1234shaik/spring-framework-petclinic.git '
            }
        }
    }
}
