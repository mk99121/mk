pipeline {
    agent any 
    tools {
        maven 'maven3 
    }   

    stages {
        stage('Build jar') {
            steps {
                script {
                    echo "Building.."
                    sh 'mvn package'
                }
            }
        }
        stage("build image") {
            steps {
                echo 'Testing..'
            }
        }
        stage("Deploy") {
            steps {
                script {
                    echo "Deploying...." 
                }
            }
        }
    }
}
