pipeline {
  agent any
  stages{
  stage('Do Something with git'){
    steps{
    sshagent(credentials: ['key_for_my_repos'])  {
      
      sh 'git status'
    }
    }
  }
  }

}
