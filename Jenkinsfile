pipeline { 
  
   agent any

   stages {
   
     stage('build') { 
        steps { 
            sh 'echo "build application..."' 
        }
     }
     
         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
     stage("testing") { 
         steps { 
           sh 'echo "Testing application..."'
         }

     }
  
   	}

   }
