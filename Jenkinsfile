node {
  stage ('SCM Checkout'){
  git 'https://github.com/mrjabde/calculator'
  }
  stage ('Compile_package'){
   def mvnHome = tool name: 'Apache Maven 3.6.3', type: 'maven' 
   sh "${mvnHome}/bin/mvn"
  }
}
