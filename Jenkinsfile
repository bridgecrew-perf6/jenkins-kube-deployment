pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                echo 'deploy app with image on K8s'
                kubernetesDeploy(configs: "deploy.yml" , kubeconfgId: "config_file_k8s" )
            }
        }
    }
}
