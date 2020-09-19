pipeline {
  agent any
  stages {
    stage('scm') {
      steps {
        git(url: 'https://github.com/teamdave204/devops.git', branch: 'master', credentialsId: 'http://192.168.1.104:8081/credentials/store/system/domain/_/credential/641c72bf-217f-43ab-8a8b-7392639bb293')
      }
    }

  }
}