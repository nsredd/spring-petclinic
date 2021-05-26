node {
    stage('Checkout'){
        git 'https://github.com/ravtellu/spring-petclinic.git'
    }

    stage('build'){
        sh 'mvn package'
    }
}
