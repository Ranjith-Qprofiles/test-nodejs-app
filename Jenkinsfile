pipeline { 
  
   agent any

   stages {
   
     stage('Build') { 
        steps { 
           sh 'echo "Build Application..."'
        }
     }
     
     stage('Test') { 
        steps { 
            'echo "Testing Application..."'
        }
      }

         stage("Deploy") { 
         steps { 
           sh 'echo "Deploying Application..."'
         }

     }
  
   	}

   }
