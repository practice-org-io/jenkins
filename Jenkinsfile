pipeline{
    agent {
        node{
            label 'ROBOSHOP'
        }
    }
    stages{
        stage('build') {
            steps{
                script{
                    sh """
                        echo "Building"
                    """
                }
            }
        }
        stage('test') {
            steps{
                script{
                    sh """
                        echo "Testing"
                    """
                }
            }
        }
        stage('deploy') {
            steps{
                script{
                    sh """
                        echo "Deploying"
                    """
                }
            }
        }
        
    }

    //post build
    post{
        always{
            echo 'I will always say Hello again'
        }
        success{
            echo "pipeline success"
        }
        failure{
            echo "pipeline failure"
        }
    }
}
    