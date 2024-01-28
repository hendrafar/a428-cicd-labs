node {
    stage('Build') {
        // Menentukan image Docker
        docker.image('node:16-buster-slim').withRun('-p 3000:3000') {
            // Steps in container
            sh 'sudo apt-get update'
            sh 'sudo apt-get install -y npm'
            sh 'npm install'
        }
    }
}