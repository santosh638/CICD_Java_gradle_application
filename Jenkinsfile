<<<<<<< HEAD
pipeline{
    agent any 
    stages{
        stage("build"){
            agent {
                docker {
                    image 'openjdk:11'
                }
            }
            steps{
                script{
                    sh 'chmod +x gradlew'
                    sh './gradlew build'
                }
            }
        }

        stage("docker build "){
            steps{
                script{
                    sh 'docker ps'
                }
            }
        }
    }
}
=======
pipeline {
    agent any   
    stages {
        stage('Build') {
            steps {
                script{
                    sh 'chmod +x gradlew'
                    sh './gradlew build'
                } 
            }
        }
    }
}    
>>>>>>> 283ad4e (jenkinsfile)
