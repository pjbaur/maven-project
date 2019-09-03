pipeline {
    /* A Declarative PIpeline */
    agent any

    stages {
        stage('Init') {
            steps {
                echo "Testing..."
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Deploy') {
            /* agent section could go here as well */
            steps {
                echo 'Code deployed.'
            }
        }
    }
}