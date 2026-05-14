pipeline {
    agent {
        label 'slave'
    }
        stages{
            //staging the pipeline script
            stage('Hello'){
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
                echo 'currect working directory'
                sh 'pwd'
                }
            }
        }
}
