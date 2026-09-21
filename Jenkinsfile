pipeline{
    agent any 
    environment{
        name : "Madhu"
    }
    stages{
        stage("Stage 1"){
            steps{
                echo "========executing A========"
            }
        }
        stage("Stage 2"){
            steps{
                sh '''
                echo "name : $name"
                '''
            }   
        }
    }
}