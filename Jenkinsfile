pipeline { 
    agent any stages { 
        stage('verifyPerformance') { 
            steps {
                 sh "mvn verify -Pperformance" 
            } 
        } 
    } 
} 