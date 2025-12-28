pipeline {
    agent any

    stages {
        stage('Checkout Code') {
    steps {
        git branch: 'main',
            url: 'https://github.com/devopsanusha2025/maven-jenkins-demo.git'
    }
}

        stage('Maven Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
