pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                echo 'deploy app with image on K8s'
                kubernetesDeploy(configs: "deploy.yml" , kubeconfigId: "config_file_k8s" )
            }
        }
    }
}
