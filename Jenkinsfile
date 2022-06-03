import java.text.SimpleDateFormat
pipeline {
    agent "demoAgent"
    
    stages {
        stage('Today DateTime') {
            steps {
                 script {
                    def dateFormat = new SimpleDateFormat("yyyyMMddhhmm")                
                    echo dateFormat.format(new Date())
                }                
            } 
        }
    }
}
