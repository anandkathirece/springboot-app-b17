pipeline {
    agent any

    stages {
        stage('git pull') {
            steps {
                git branch: 'main', url: 'https://github.com/anandkathirece/springboot-app-b17.git'
            }
        }
        stage('package') {
            steps {
               sh 'mvn clean package'
            }
        }
    }
}
