pipeline {
    agent {
        node {
            label "maven-2"
        }
    }

    stages {
        stage('build') {
            steps {
                git branch: 'main', url: 'https://github.com/rajivsiddiqui/AR-p2.git'
            }
        }
    }
}