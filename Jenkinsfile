pipeline{
    agent any
    stages{
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-pipelines"
            }
        }
        stage("add some files"){
            steps{
                sh "touch ~/jenkins-pipelines/file.txt"
                sh "ls -al"
            }
        }
    }
}