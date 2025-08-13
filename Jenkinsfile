pipeline {
    agent any
    stages {
        stage('Deploy to Kubernetes') {
            steps {
                echo "Deploying application to Kubernetes..."
                sh 'kubectl apply -f k8s-deployment.yml'
                echo "Deployment complete."
            }
        }
    }
}
