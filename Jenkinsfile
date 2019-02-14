pipeline {
  agent any
  stages {
    stage('Example Build') {
      steps {
        ansiblePlaybook('playbook.yml') {
          inventoryPath('host.ini')
        }
      }
    }
  }
}
