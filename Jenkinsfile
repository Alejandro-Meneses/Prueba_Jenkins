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
                sh 'python3 "print("Hola desde Python ejecutado por Jenkins 🚀")

for i in range(1, 6):
    print(f"Contador: {i}")"'
            }
        }
    }
}
