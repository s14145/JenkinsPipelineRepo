// Jenkins pipeline (Declarative Pipeline: code to create jobs and run them in pipeline)

pipeline{
  agent any
    stages{
      stage('One'){
        steps{
            echo 'Hi, this is the demo of jenkins pipeline'
             }
                  }
      stage('Two'){
        steps{
              input('Do you want to proceed?')
                  }
             }
    }
}
      /*
      stage('Three'){
             when{
                    not{
                            branch "master"
                        }
             }
        steps{
                  echo "Hello"
             }
                  }
                  
      stage('Four'){
        parallel{
          stage('Unit Test'){
            steps {
                    echo "Running the unit test"
                  }
                            }
          stage('Integration Test'){
            agent{
              docker{
                       reuserNode false
                       image 'ubuntu'
                    }
                }
            steps{
                    echo 'Running the integration test...'
                  }
                                   }
                  }
      }
    }
    */
      

