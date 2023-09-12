pipeline {
    agent {
        node {
            label "maven-2"
        }
    }
environment {
    PATH = "/opt/apache-maven-3.9.4/bin:$PATH"
}
    stages {
        stage('build') {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
