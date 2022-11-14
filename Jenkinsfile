pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git credentialsId: 'github', url: 'https://github.com/NibeditaBishoyi/jenkinsrepo.git'
                
            }
        }
        stage('compile') {
            steps {
                echo 'Hello World'
                sh 'mvn compile'
                
            }
        }
    }
}
