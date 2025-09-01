pipeline {
    agent {
        label 'linux-node'
    }
    stages {
        stage('Build') {
            steps {
                
                    sh 'echo "Building the project..."'
                    sh 'cd /home/jtiongzon/node-webapp'
                    sh 'docker build .'
                    sh 'docker run -p 3000:3000 node-webapp'
                
            }
        }
    }
}
