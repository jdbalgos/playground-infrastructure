pipeline {
  agent any
  stages {
    stage('Create Server') {
      steps {
        sh 'ansible-playbook --vault-pass-file=~/.ansible_pass proxmox-infra.yml'
      }
    }
  }
}
