// Jenkinsfile (Scripted Pipeline)
node() { // node/agent

  stage('Stage 1') {
    def example = load "${rootDir}/common.groovy"

    example.mycommoncode()
    echo 'Hello World' // echo Hello World
  }
}