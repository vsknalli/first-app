node{
    stage('SCM checkout'){
        git 'https://github.com/vsknalli/first-app/'
    }
    stage('Compile-Package'){
        sh '/opt/apache-maven-3.8.6/bin/mvn package'
    }
}
