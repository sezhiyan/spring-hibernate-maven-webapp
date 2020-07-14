node{
  stage('SCM Checkout'){
  git'https://github.com/sezhiyan/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('Compile-Package'){
  def MAVEN_HOME = tool name: 'maven', type: 'maven'
sh"${MAVEN_HOME}/bin/mvn package"
}
}
