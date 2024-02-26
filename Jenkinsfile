pipeline
       {
        agent any
            stages
                 {
                 stage("Git")
                      {
                      steps
                        {
                        git "https://github.com/Dwaraka224/Feb26_Jenkinsfile.git"
                        }
                      }
                        stage("Run")
                            {
                            steps
                               {
                               sh "python3 main.py"
                               sh "java Demo.java"
                               }
                             }
}
 }
  
