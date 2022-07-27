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
           sh 'echo "testingvvv application..."'
        }
      }

         stage("Deploy  nodejs..  application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
