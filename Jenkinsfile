pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('sql'){
            steps {
                SQLCMD -S SUKHRAM-DOTNET\SOFTSYSSOL -U sa -P 123 -i C:\PS\SQLScript\backupscript.sql
            }
        }
    }
}
