node {
    docker.image('node:lts-buster-slim').withRun('-p 3000:3000') {
        stage('Build') {
            sh 'npm install'
        }
    }
}
