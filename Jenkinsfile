pipeline {
    agent {label 'MASTER'}
    stages {
        stage('Checkout'){
            steps {
                git 'https://github.com/dummyrepos/spring-petclinic.git' 
            }
        }
        stage('Build'){
            steps {
                sh 'mvn package'
            }
        }
    }
}
