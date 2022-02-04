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
        
                stage('Test On Docker') {
                    agent {
                        label "Docker"
                    }
                    steps {
                        echo "Running on Docker"
                    }                    
                }
            
        
    }
}
