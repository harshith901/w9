pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    // Build your Docker image
                    bat 'docker build -t w9-dd-app .'
                   // bat 'docker tag w9-dd-app:latest shiv4j/w9-dh-app:latest'
                  //  bat 'docker push shiv4j/w9-dh-app:latest'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run tests here if you have any
                    echo 'Running tests...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Deploy your Docker image
                    //bat 'minikube start'
                    //bat 'kubectl apply -f my-kube1-deployment.yaml'
                    //bat 'kubectl apply -f my-kube1-service.yaml'
                   // bat 'minikube dashboard'
                    //bat 'kubectl get services'
                    //echo 'Deploying application...'
                }
            }
        }
    }
}
