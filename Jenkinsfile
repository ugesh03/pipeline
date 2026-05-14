pipeline {
    agent {
        label 'slave'
    }
        stages{
            //staging the pipeline script
            stage('Hello'){
                 agent {
        label 'Build-In Node'
    }
                steps{
                echo 'Jenkins from Master server'
                }
            }
            
            //2nd stage of the pipeline
            stage('Root'){
                steps{
                echo 'Print the root directory spcace'
                sh 'df -h /'
                }
            }
            //3rd stage of the pipeline present working directory
            stage('working directory'){
                steps{
                echo 'current working directory'
                sh 'pwd'
                }
            }
        }
}
