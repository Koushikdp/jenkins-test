pipeline{
    agent any
    stages{
        stage('NODE details'){
             environment{
                    Name="koushik"
                }
            steps{
                echo "im running on this node : $NODE_NAME"
                echo "im running with this build number: $BUILD_NUMBER"
                echo "Hi from $env.Name"
                echo "this is my branchname: $BRANCH_NAME
            }
        }
    }
}
