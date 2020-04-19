node{
   stages{
     Stage('SCM checkout'){
        steps{
           git 'https://github.com/sanbar-web/maven'
        }          
       }
    Stage('Compile package'){
       steps{
          bat 'mvn package'
       }      
    }
   }  
  }
