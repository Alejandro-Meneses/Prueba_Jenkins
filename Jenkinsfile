pipeline {
    agent any

    stages {
        stage('Comprobar Python') {
            steps {
                sh 'python3 --version || echo "Python no instalado"'
            }
        }

        stage('Ejecutar script Python') {
            steps {
                sh 'python3 script.py'
            }
        }
    }
}
