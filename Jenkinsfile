pipeline {
  agent any
  stages{
  stage('Do Something with git'){
    steps{
    sshagent(credentials:['60:8d:d4:07:38:4c:66:bc:48:74:27:94:a9:9e:4f:83']){
      sh 'git status'
    }
    }
  }
  }

}
