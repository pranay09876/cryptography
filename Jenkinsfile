pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                echo 'Hello World DEV'
                bat 'git clone "https://github.com/pranay09876/cryptography.git"'
            }
        }
        stage('QA') {
            steps {
                echo 'Hello World1 QA'
            }
        }
        stage('UAT') {
            steps {
                echo 'Hello World uat'
            }
        }
        stage('PreProd') {
            steps {
                echo 'Hello World preprod'
            }
        }
        stage('PROD') {
            steps {
                echo 'Hello World prod'
            }
        }
    }
}
