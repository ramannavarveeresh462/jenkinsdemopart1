pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'building'
            }
        }
        stage('Test') { 
            steps {
                echo 'testing'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'deploying'
                
            }
        }
    }
    
       stage('Notify') { 
           steps {
               echo 'Notifying'
                
            }
        }
    
   // post {
   // failure {
        //mail to: 'ramannavarveeresh462@gmail.com',
         //    subject: "Please check: ${currentBuild.fullDisplayName}",
          //   body: "Something is wrong with ${env.BUILD_URL}"
   // }
//}
}
