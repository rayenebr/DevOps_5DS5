pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git branch: 'main', url: 'https://github.com/rayenebr/DevOps_5DS5.git'
            }
        }
        stage('Maven') {
            steps {
                sh "mvn clean"
            }
        }
        
    }
}
