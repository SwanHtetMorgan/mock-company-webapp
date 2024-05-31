pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   agent any
    stages{
        stage("Build")
        {
            steps {
              sh './gradlew assemble'
            }
        }
        stage("Test")
                {
                    steps{
                        echo "Application is under Testing"
                        sh './gradlew test'
                    }
                }
    }
}
