pipeline{
    agent{
        label "node"
    }
    stages{
        stage("Restore"){
            steps{
                bat "dotnet restore"
            }
        }
    }

    stages{
        stage("Build"){
            steps{
                bat "dotnet build"
            }
        }
    }
    
    stages{
        stage("Test"){
            steps{
                bat "dotnet test"
            }
        }
    }
}