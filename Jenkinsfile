node {
  stage('Do Something with git'){
    sshagent(credentials: ['key_for_my_repos'])  {
      
      sh 'git ls-remote-h --refs git@github.com:srivatsanv1991/weatherForecast.git master |awk "{print $1}"'
    }
    
  }

}
