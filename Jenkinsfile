pipeline{
    //Pipeline demo code
    tools{
        // what tool version to use for build stages
        maven 'mymaven'
    }
    
    agent any
    
    stages{
        
        stage ('CloneRepo')
        {
            steps{
             echo 'This is stage 1'
              git 'https://github.com/Sonal0409/DevOpsCodeDemo.git'  
            }
        }
        
        stage ('Compile')
        {
            steps{
                
             sh  'mvn compile'
                
            }
        }
       
        
        
        
    }
    
    
    
}
