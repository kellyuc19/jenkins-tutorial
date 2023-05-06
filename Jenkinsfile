pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir ~/jenkins-tutorial-test"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
             stage('Make Kelly's Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/Kellyfile1 ~/jenkins-tutorial-test/Kellyfile2"
                }
            }    
        }
}
