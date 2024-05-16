pipeline {
    agent any
    tools {
        maven ' maven '
    }
    stages {
        stage ('SCM') {
            steps {
                git ' https://github.com/1234shaik/spring-framework-petclinic.git '
            }
        }
        stage ('Maven Build') {
            steps {
                bat ' mvn -f pom.xml clean install '
            }
        }
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
