pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                echo 'Hello, Maven'
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './mvn.sh'
            }
        }
    }
}
