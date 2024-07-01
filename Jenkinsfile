pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    sh 'python3 main.py'
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
