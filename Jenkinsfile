node {
    stage('ClonarRepo') {
        git 'https://github.com/priximmo/jenkins-helloworld.git'
    }
    stage('Buidear') {
        sh 'javac Main.java'
    }
    stage('Correr') {
        sh 'java Main'
    }
}