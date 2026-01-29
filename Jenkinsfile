pipeline{
     agent any
     stages{
        stage('print env'){
            steps{
                script {
                    if (env.BRANCH_NAME == "main") {
                        sh '''
                            echo "Please follow the CR process" 
                            
                             
                        '''
                        
                    }
                    else {
                        echo "Branch is not main, safe to proceed"
                    }
                }
            }
        }
     }
}