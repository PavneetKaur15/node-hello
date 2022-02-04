// Script //
//node {
//    checkout scm 
//    /* .. snip .. */
//}
// Declarative not yet implemented //
// Declarative //
// Declarative //
pipeline {
    agent none
     stages {
        stage('Run Tests') {
            parallel {
                 stages {
                         stage('Build') {
                             agent {
                                        label "linux"
                             }
                             steps {
                                     echo 'Building..'
                             }
                         }
                         stage('Test') {
                                        agent {
                                         label "Docker"
                             }
                             steps {
                                      echo 'Testing..'
                             }
                         }
                  }
            }
}
     }

    
