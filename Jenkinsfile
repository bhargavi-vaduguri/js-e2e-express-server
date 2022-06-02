node('jdk11-mvn3.8.4') {
    stage('git') {
        git 'https://github.com/bhargavi-vaduguri/js-e2e-express-server.git'
    }
    stage('build') {
        sh 'npm install'
    }
}    