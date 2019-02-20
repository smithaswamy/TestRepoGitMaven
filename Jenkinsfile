node{
stage('SCM checkout'){
git 'https://github.com/smithaswamy/TestRepoGitMaven'
}
stage('Compile-Package'){
sh 'mvn package'
}
}
