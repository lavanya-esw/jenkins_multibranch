pipeline{
     agent any
     stages{
        stage('print env'){
            steps{
                script{
                    when {
                        expression { "env.BRANCH_NAME" == "main"}
                        script{
                            sh """
                            echo "please follow the CR process"
                            """
                        }
                    }
                }
            }
        }
     }
}