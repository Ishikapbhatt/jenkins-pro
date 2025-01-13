pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...'
                checkout scm
            }
        }

        stage('Run Shell Script') {
            steps {
                echo 'Running shell script...'
                sh './script.sh'   // Runs the script.sh file
            }
        }
    }
}
