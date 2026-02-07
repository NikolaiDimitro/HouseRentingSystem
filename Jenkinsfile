pipeline{

    agent{
        label any
    }

    stages{
        stage("Restore"){
            steps{
                bat "dotnet restore"
            }
        }
    
        stage("Build"){
            steps{
                bat "dotnet build"
            }
        }
    
        stage("Test"){
            steps{
                bat "dotnet test"
            }
        }
}
}