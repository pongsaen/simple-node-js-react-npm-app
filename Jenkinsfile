pipeline {
    agent any
    stages{
        stage('Build'){

            steps{
                bat 'npm install'
            }

        }

        stage('Run Powershell'){

            steps{
                powershell 'C:/my-script/Untitled1'
            }

        }


    }
}