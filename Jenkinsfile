pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application now..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying NodeJS application now..."'
         }

     }
  
   	}

   }
