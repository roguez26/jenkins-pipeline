pipeline {
    agent any
    stages {
        stage ( ’ Clonar c d i g o ’) {
            steps {
                git https://github.com/d0ubl3dd/LotteryServer.git
            }
        }
        stage ( ’ Compilar ’) {
            steps {
                sh ’ echo " Compilando el proyecto ..." ’
            }
        }
        stage ( ’ Pruebas ’) {
            steps {
            sh ’ echo " Ejecutando pruebas ..." ’
            }
        }
    }
}
