node{
    stage('SCM Checkout'){
    git 'https://github.com/amritendu-gintaa/java-hello-world-with-maven'
    }
    stage('Compile-Package-Install'){
    sh 'mvn clean install'
    }
}
