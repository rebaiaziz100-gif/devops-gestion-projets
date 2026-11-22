pipeline {
    agent any
    tools { maven 'M2_HOME' }
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rebaiaziz100-gif/devops-gestion-projets.git'
            }
        }
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}
