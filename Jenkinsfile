pipeline{
    agent {
        node{
            label 'ROBOSHOP'
        }
    }
    environment{
        COURSE ="Jenkins"
    }
    options{
        disableConcurrentBuilds()
    }
    stages{
        stage('build') {
            steps{
                script{
                    sh """
                        echo "Building"
                        echo $COURSE
                        sleep 5
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
    