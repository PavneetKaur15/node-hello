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
                stage('Test On Linux') {
                    agent {
                        label "linux"
                    }
                }
                stage('Test On Docker') {
                    agent {
                        label "docker"
                    }
                }
            }
        }
    }
}
