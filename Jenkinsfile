node {
    stage('Clone') {
        git 'https://github.com/amal-mhd/jenkins-helloworld.git'
    }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
