pipeline {
    agent any

    stages {
        stage('Clonar repositorio') {
            steps {
                sh 'echo "Jenkins mola >> Jenkins.txt"'
            }
        }

        stage('Comprobar contenido') {
            steps {
                sh 'cat Jenkins.txt'
            }
        }

    
    }
}
