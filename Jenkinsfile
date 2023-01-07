pipeline {
    agent { label "agentfarm" }
    stages {
        stage('Delete the workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Installing Ansible') {
          steps {
            sh 'sudo apt-get update -y && sudo apt-get upgrade -y'      
            sh 'sudo apt-get update -y && sudo apt-get upgrade -y'
          }
        }
        stage('Third Stage') {
            steps {
                echo "Third stage"
            }
        }
    }
} 
