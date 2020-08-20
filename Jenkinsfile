pipeline {
    agent any

    stages {
        stage("Make Directory") {
            steps{
                sh "rm -r ~/jenkins-tutorial-test"
                sh "mkdir ~/jenkins-tutorial-test"
            }
        }
        stage("Make Files") {
            steps{
                sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
            }
        }
    }
}
