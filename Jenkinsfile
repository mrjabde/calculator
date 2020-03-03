node {
  stage ('SCM Checkout'){
  git 'https://github.com/mrjabde/calculator'
  }
  stage ('compile_package'){
    def mvnHome= tool name: 'localMaven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
