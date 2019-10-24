pipeline {
  agent any
  stages {
    stage ("SCM CHECKOUT") {

    steps {
        git branch: 'develop',
        url: 'ssh://git@github.com:Jifflenow/ui-next.git'
        sh "ls -lat"
    }
    
    }
  }

}
