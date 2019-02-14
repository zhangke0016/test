pipeline {
  agent any
  stages {
    stage('Example Build') {
      steps {
        ansiColor('xterm') {
           ansiblePlaybook(
            playbook: 'playbook.yml',
            inventory: 'host.ini',
            colorized: true)
        }
      }
    }
  }
}
