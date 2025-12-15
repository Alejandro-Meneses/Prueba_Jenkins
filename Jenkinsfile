pipeline {
    agent any

    stages {
        stage('Crear archivo') {
            steps {
                sh '''
                    pwd
                    echo "Jenkins mola" > Jenkins.txt
                    ls -l
                '''
            }
        }

        stage('Comprobar contenido') {
            steps {
                sh '''
                    pwd
                    ls -l
                    cat Jenkins.txt
                '''
            }
        }

        stage('Mensaje final') {
            steps {
                echo 'Pipeline ejecutado correctamente 🚀'
            }
        }
    }
}
