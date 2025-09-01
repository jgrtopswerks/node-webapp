pipeline {
    agent {
        label 'linux-node'
    }
    stages {
        stage('Build') {
            steps {
                
                    sh 'echo "Building the project..."'
                    sh 'ls -la'
                    sh 'cd /home/jtiongzon/node-webapp'
                    sh 'docker build .'

                
            }
        }
    }
}
