node{
 stage('SCM checkout'){
  git 'https://github.com/urmila1262/hello-world'
  }
 stage('compile-package'){
  //get maven home path
  tool name: 'Maven 3.0.5', type: 'maven'
  sh "${mvnhome}/usr/share/maven package"
  }
 } 
