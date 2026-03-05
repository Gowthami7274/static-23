pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git 'https://github.com/Gowthami7274/static-23.git'
            }
        }

        stage('Deploy Website') {
            steps {
                sh 'cp -r * /var/www/html/'
            }
        }

    }
}
