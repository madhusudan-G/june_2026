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
        stage("Stage 3"){
            steps{
                sh '''
                echo "This is stage 3"
                '''
            }
        }
        stage("Stage 4"){
            steps{
                sh '''
                echo "This is stage 4"
                '''
            }
        }
        stage("Stage 5"){
            steps{
                sh '''
                echo "This is stage 5"
                '''
            }
        }
    }
}
