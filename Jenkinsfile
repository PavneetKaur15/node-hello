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
            
                stage('Test On Docker') {
                    agent {
                        label "docker"
                    }
                    steps {
                        echo "Running on Docker"
                    }                    
                }
            
        }
    }
}
