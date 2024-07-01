pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                // Use a Python Docker image to run the script
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
