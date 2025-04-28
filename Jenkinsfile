pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Basheer-dev/tweet-trend-new.git'
            }
        }
    }
}
