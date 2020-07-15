node{
  stage('SCM Checkout'){
  git'https://github.com/sezhiyan/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('clear'){
  def mvn_Home = tool name: 'maven-3', type: 'maven'
bat 'mvn clean'
}
}
