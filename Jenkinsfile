pipeline {
          agent {label 'Slave1'}
         stages {
                 stage('Build') {
                 steps {
                     echo 'Hi, DevOps Engineer. Starting to build the App.'
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
                 
                 stage('PRODUCTION') {
                     steps {
                                echo "App is Prod Ready"
                              }
                 
              }
         }
         
}
