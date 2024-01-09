pipeline {
    agent {
        node('slave-node') 
    }

    stages {
        stage('git-clone') {
            steps {
                git branch: 'main', url: 'https://github.com/niyazahmad987/tweet-trend-new.git'
            }
        }
    }
}

