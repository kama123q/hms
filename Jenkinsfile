pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                sshagent(credentials : ['kam']) {
                    sh 'ssh -tt -o StrictHostkeychecking=no centos@3.19.32.113  touch j1'
          
        }
                
                     
                }
            }
        }
        }
