node{
    stage('SCM Checkout'){
    git 'https://github.com/amritendu-gintaa/java-hello-world-with-maven'
    }
    stage('Checkout'){
        git checkout develop
    }
    stage('Compile-Package-Install'){
    sh 'mvn clean install'
    }
}
