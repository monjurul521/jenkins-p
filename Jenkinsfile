pipeline { 
  
   agent any
     
   stages {
   
     stage('Install ffDependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testingvvv ggapplication..."'
        }
      }

         stage("Deploy  nodejs..  application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
