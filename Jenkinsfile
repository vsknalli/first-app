pipeline{
  agent any
  stage('scm checkout'){
    git 'https://github.com/vsknalli/first-app/'
  }
  stage(Compile-Package){
    sh 'mvn package'
  }
}