node {
    stage('Build') {
        // Menentukan image Docker dan argumen
        docker.image('node:16-buster-slim').withRun('-p 3000:3000') {
            // Langkah-langkah dalam container
            sh 'npm install'
        }
    }
}