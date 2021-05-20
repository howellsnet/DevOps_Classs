pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build maven') {
            steps {
                sh 'mvn --version'
            }
        }
       stage('build python') {
           steps {
               sh 'python --version'
            }
        }
    }
}

