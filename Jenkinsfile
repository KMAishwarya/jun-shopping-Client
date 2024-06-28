pipeline {
    agent any
    stages{
        stage("Build"){
            steps{
                sh "dotnet restore"
            }
        }
        stage("Test"){
            steps{
                 echo "this is test"
            }
        }
    }
}
