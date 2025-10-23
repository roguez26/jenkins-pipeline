pipeline {
    agent any
    stages {
        stage('Clonar código') {
            steps {
                git url: 'https://github.com/d0ubl3dd/LotteryServer.git'
            }
        }
        stage('Compilar') {
            steps {
                sh 'echo "Compilando el proyecto..."'
            }
        }
        stage('Pruebas') {
            steps {
                sh 'echo "Ejecutando pruebas..."'
            }
        }
    }
}
