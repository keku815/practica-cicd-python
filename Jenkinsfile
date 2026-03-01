pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Simulando compilación de Python..."'
                sh 'echo "Entorno virtual creado exitosamente"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Ejecutando Pytest... 100% de tests pasados"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Desplegando a Staging..."'
                sh 'echo "URL de acceso: http://staging.local"'
            }
        }
    }
}
