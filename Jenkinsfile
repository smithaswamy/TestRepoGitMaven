node{
stage('SCM checkout'){
git 'https://github.com/smithaswamy/TestRepoGitMaven'
}
stage('Compile-Package'){  
 def mvnHome= tool name: 'Maven_home', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
