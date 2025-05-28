pipeline {
    agent any

    stages {
        stage('Install Docker and Run Container') {
            steps {
                sh '''
                ansible-playbook -i inventory.ini install_docker.yaml
                '''
            }
        }
    }
}
