import java.text.SimpleDateFormat
pipeline {
    agent any
    
    stages {
        stage('Today DateTime') {
            steps {
                 script {
                    def dateFormat = new SimpleDateFormat("yyyyMMddhhmm")                
                    today = dateFormat.format(new Date())                
                    echo today
                }                
            } 
        }
    }
}
