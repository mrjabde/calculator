node {
  stage ('SCM Checkout'){
  git 'https://github.com/mrjabde/calculator'
  }
  stage ('Compile_package'){
    sh 'mvn package'
  }
}
