pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                echo 'deploy app with image on K8s'
                sh 'kubectl apply -f deploy.yml --kubeconfig /admin.conf' 
            }
        }
    }
}
