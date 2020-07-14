node{
  stage('SCM Checkout'){
  git'https://github.com/sezhiyan/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('Compile-Package'){
  def mvnHome = tool name: 'maven', type: 'maven'
sh"${mvnHome}/bin/mvn package"
}
}
