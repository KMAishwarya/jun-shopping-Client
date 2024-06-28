pipeline {
    agent any
    stages{
        stage("Dotnet Restore"){
            steps{
                sh "dotnet restore"
            }
        }
        stage("Dotnet Build"){
            steps{
                sh "dotnet build -c reslase -o /opt"
            }
        }
        stage("Dotnet Publish"){
            steps{
                sh "dotnet publish -c release -o /opt"
            }
        }
    }
}
