node {
    stage("scm"){
       
        git 'https://github.com/siva244/spring-petclinic.git'   
    }
       stage("build"){
        sh 'mvn package'
    }
}
