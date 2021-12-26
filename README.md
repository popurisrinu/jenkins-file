# jenkins-filepipeline{
    agemt any
    stages
    {
        stage("build")
        {
            steps{
                echo "bulding the codee.........."
                bat "mvn clean"
            }
        }
        stage("deployment")
        {
            steps{
                echo "deploy the code..........."
            }
        }
        stage("test")
        {
            steps{
                echo "test the code......."
            }
        }
    }
    
}
