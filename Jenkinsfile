pipeline {
    agent any

    stages {
        stage('Run Ansible Playbook') {
            steps {
                ansiblePlaybook(
                    playbook: 'Assessement1.yaml',
                    become: true
                )
            }
        }
    }
}
