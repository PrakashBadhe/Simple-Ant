pipeline {
    agent any
    
    stages {
        stage('Checkout Github') {
            steps {
                echo 'Checking out from git hub'
               // println "The groovy runtime version is $GroovySystem.version"
              //  git branch: 'main', credentialsId: 'Jenkins-User', url: 'https://github.com/PrakashBadhe/Simple-Ant'
            }
        }
        stage('Accessing apis from external server'){
          steps {
                 System.out.println "Second Stage Here"          
             
                 def data = 100
                 def num = 2334
                 def sum = data + num
                 System.out.println "Sum is $sum"             
              
             }
                
            }
            
        }
        
        
    }
