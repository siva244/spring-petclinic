node {
    stage("scm"){
       
        git url:'https://github.com/siva244/spring-petclinic.git'   
    }
       stage("build"){
        sh 'mvn package'
    }
}
