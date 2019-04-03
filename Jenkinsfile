pipeline {
  agent any
  stages{
  stage('Do Something with git'){
    steps{
    sshagent(credentials: ['mygithubkey'])  {
      
      sh 'git status'
    }
    }
  }
  }

}
