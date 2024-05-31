pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   agent any
    stages{
        stage("Build")
        {
            steps{
                echo "Application is Building..."
                sh './gradle assemble'
            }
        }
        stage("Test")
                {
                    steps{
                        echo "Application is under Testing"
                        sh './gradle test'
                    }
                }
    }
}
