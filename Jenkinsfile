// Jenkinsfile (Scripted Pipeline)
node() { // node/agent

  stage('Stage 1') {
       checkout scm
    def rootDir = pwd()
    println("Current Directory: " + rootDir)
    def example = load "${rootDir}/common.groovy"

    example.mycommoncode()
    echo 'Hello World' // echo Hello World
  }
}