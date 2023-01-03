pipeline {
    agent any
    parameters {
     string description: 'cron', name: 'cron'
     }
     
      stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('print'){
           steps{
               echo '${params.cron}'
               }
        }
     }
}
