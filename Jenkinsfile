pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    echo 'script here'
                }
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution completed.'
        }
        success {
            echo 'This pipeline succeeded.'
        }
        failure {
            echo 'This pipeline failed.'
        }
    }
}
