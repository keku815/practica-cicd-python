pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                    python3 -m venv venv
                    . venv/bin/activate
                    pip install -r requirements.txt
                '''
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Ejecutando pruebas unitarias..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Despliegue simulado a entorno de staging completado"'
            }
        }
    }
}
