pipeline {

    agent {
        node {
            label 'maven'
        }
    }
    environment { 
        PATH = "/opt/apache-maven-3.9.11/bin:$PATH"
    }
  stages {

        stage('stage1') {
            steps {
                echo "HELLOWORLD"
            }
        }
      stage('build') {
            steps {
                echo "this is maven stage"
                sh 'mvn --version'
            }
        }
  }
}
