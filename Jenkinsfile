pipeline {
    agent any
    stages {
        stage('build')
            step{
                sh "mvn compile"
            }
        }
        stage('test'){
            step{
                sh "mvn test"
            }
        }

}
