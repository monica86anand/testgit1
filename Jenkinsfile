pipeline
{
  agent any
  
    stages
  {
    stage("step1")
    {
      steps
      {
        echo "hello"
        
      }
    }   
     stage("2")
    {
      when{
        branch "master"
      }
      steps
      {
        echo "in condi"
      }
    }
  }
}
          
      
    
