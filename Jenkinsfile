pipeline {
    agent any // Or specify a node where Maven is installed

    tools {
        // Use the name configured in Global Tool Configuration
        maven 'M3' 
    }

    stages {
        stage('Build and Install') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
