import java.text.SimpleDateFormat
pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Hello') {
            steps {
                def dateFormat = new SimpleDateFormat("yyyyMMddhhmm")                
                echo dateFormat.format(new Date())
            }
        }
    }
}
