pipeline {
    agent {
        label {
            label 'built-in'
            customWorkspace '/mnt/sita'
        }
    }
    
          stages {
              stage ('stage-1') {
                  steps {
                      sh "echo 'this is master branch' "
                      sh "touch fileM1"
                  }
                  
              }
          }
}
