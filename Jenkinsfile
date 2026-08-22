pipeline{
    agent any
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
}
    