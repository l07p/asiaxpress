pipeline {
    agent any

    stages{
        stage('Run Python Script from root asiaxpress') {
            steps {
                script {
                sh 'python3 main.py'
                }
            }
        }
    }
    post {
        always {
            echo 'This stage runs after all stages are complete.'
        }
    }
}
