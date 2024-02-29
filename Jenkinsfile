pipeline{
    agent {
        label "worker"
    }
    stages{
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-pipelines || true"
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
