pipeline{
     agent any
     stages{
        stage('print env'){
            steps{
                script{
                    sh """
                        env 
                        echo "hello world" 
                    """
                }
            }
        }
     }
}