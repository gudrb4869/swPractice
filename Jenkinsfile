import java.text.SimpleDateFormat
pipeline {
    agent {
        label "demoAgent"
    }
    
    stages {
        stage('Print') {
            steps {
                 script {
                    def dateFormat = new SimpleDateFormat("yyyyMMddhhmm")                
                    echo dateFormat.format(new Date())
                }                
            } 
        }
    }
}
