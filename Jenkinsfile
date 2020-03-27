node{

  stage('SCM checkout'){
    git 'https://github.com/Schlenkian07/Gitdemo'
  }
  
  stage('Compile-package'){
    sh 'mvn package'
  }
  
}
