pipeline {
    agent any

    stages {
        stage('Clonar repositorio') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/USUARIO/REPO.git',
                    credentialsId: 'github-repo-token'
            }
        }

        stage('Comprobar contenido') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Mensaje prueba') {
            steps {
                sh 'echo "Pipeline Jenkins funcionando correctamente"'
            }
        }
    }
}
