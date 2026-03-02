pipeline {
   agent any 
    
    stages{
        stage('build'){
            steps{
                echo "welcome to jenkins"
            }
        }
        stage('test'){
            steps{
                echo "welcome to testingteam"
                sh 'touch day'
            }
        }
        stage('deploy'){
            steps{
                echo "welcome to deploymentteam"
                sh 'pwd'
            }
        }
    }

}
