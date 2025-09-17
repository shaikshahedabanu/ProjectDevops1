pipeline {

    agent {
        node {
            label 'maven'
        }
    }
    // environment { 
    //     PATH = "/opt/apache-maven-3.9.11/bin:$PATH"
    // }
  stages {

        stage('stage1') {
            steps {
                echo "HELLOWORLD"
            }
        }
      stage('stage2') {
            steps {
                echo "this is stage2"
                sh 'pwd'
            }
        }
  }
}
