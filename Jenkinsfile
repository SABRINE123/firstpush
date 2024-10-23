pipeline{
    agent any
    tools {
        maven 'Maven3' // Use the name you specified in Global Tool Configuration
        }
    stages{
        stage('Build'){
            steps{
                sh 'mvn clean install'
            }
        }
        stage ('Test'){
            steps{
                sh 'mvn test'
            }
        }
    }

}