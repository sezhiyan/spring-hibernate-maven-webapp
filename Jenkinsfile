node{
  stage('SCM Checkout'){
  git'https://github.com/sezhiyan/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('Compile-Package'){
  def mvn_Home = tool name: 'maven', type: 'maven'
sh"${mvn_Home}/bin/mvn package"
}
}
