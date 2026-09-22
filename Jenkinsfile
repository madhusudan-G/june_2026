pipeline {
    agent any

    parameters {
        string(name: 'Branch', defaultValue: 'Madhu', description: 'To deploy continuous CI/CD')
    }

    stages {
        stage("Stage 1") {
            steps {
                echo "========executing A========"
            }
        }

        stage("Stage 2") {
            steps {
                sh '''
                    echo "This is stage 2"
                '''
            }
        }

        stage("Stage 3") {
            steps {
                sh '''
                    echo "This is stage 3"
                '''
            }
        }

        stage("Stage 4") {
            steps {
                sh '''
                    echo "This is stage 4"
                '''
            }
        }

        stage("Stage 5") {
            steps {
                sh '''
                    echo "This is stage 5"
                '''
            }
        }
    }
}
