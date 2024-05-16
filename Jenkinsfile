pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
              git branch: 'main', url: 'https://github.com/1234shaik/springpetclinic.git'
            }
        }
        /* stage ('Maven Build') {
            steps {
                bat 'mvn clean'
            }
        } */
    }
}

/* pipeline {
    agent any
    stages {
        stage ("scm") {
            steps {
                git ' https://github.com/1234shaik/spring-framework-petclinic.git '
            }
        }
    }
} */
