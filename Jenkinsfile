pipeline {
    agent any

    stages {
        stage('Run Ansible Playbook') {
            steps {
                dir('/etc/ansible/') {
                    git branch: 'master',
                        url: 'https://github.com/jh9922/Assessement1'
                    sh 'ansible-playbook Assessement1.yaml'
                }
            }
        }
    }
}
