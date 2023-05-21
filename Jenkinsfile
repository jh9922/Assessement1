pipeline {
    agent any

    stages {
        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook -i hosts Assessement1.yaml'
            }
        }
    }
}
