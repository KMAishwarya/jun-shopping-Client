pipeline {
    agent any
    stages {
        stage("Dotnet Install") {
            steps {
                sh "sudo yum install dotnet -y"
            }
        }
        stage("Dotnet Restore") {
            steps {
                sh "dotnet restore"
            }
        }
        stage("Dotnet Build") {
            steps {
                sh "dotnet build -c release -o /opt"
            }
        }
    }
}
