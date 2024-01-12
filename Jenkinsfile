pipeline {
    agent {
        node {
            label "maven"
        }
    }

    stages {
        stage('clone-code') {
            steps {
               git branch: 'main', url: 'https://github.com/kpatil1598/tweet-trend-new.git'
            }
        }
    }
}
