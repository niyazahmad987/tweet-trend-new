pipeline {
    agent {
        node('slave-node') 
    }

environment {
    PATH= "/opt/apache-maven-3.8.8/bin:$PATH" 
}
    stages {
        stage('build') {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
