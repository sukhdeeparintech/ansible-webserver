pipeline {
    agent { label  "agentnode" }
    stages {
        stage('Delete the workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Second Stage') {
            steps {
                echo "Second stage"
            }
        }
        stage('Third Stage') {
            steps {
                echo "Third stage"
            }
        }
    }
} 
