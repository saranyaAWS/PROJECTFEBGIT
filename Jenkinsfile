pipeline {
   agent any 
    
    stages{
        stage("build"){
            step{
                echo "welcome to jenkins"
            }
        }
        stage("test"){
            step{
                echo "welcome to testingteam"
                sh 'touch day'
            }
        }
        stage("deploy"){
            step{
                echo "welcome to deploymentteam"
                sh 'pwd'
            }
        }
    }

}
