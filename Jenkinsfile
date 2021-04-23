pipeline {
    agent any
    stages {
        stage('Ansible Task') {
            steps {
              sh 'ansible-playbook -i inventory windows.yml'
            }
        }
    }
}