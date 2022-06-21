pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh "gcc HelloGit.c"
                sh "./a.out"
            }
        }
    }
}
