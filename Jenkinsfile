node{

  stage('SCM checkout'){
    git 'https://github.com/Schlenkian07/Gitdemo'
  }
  
  stage('Compile-package'){
    
    def mvnHome = tool name: 'maven-3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
  
}
