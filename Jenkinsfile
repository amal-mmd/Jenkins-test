node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/amal-mmd/Jenkins-test.git'
    }
    stage('Build') {
        sh '''javac Main.java
           '''
    }
    stage('Run') {
        sh '''java Main
           '''
    }
}
