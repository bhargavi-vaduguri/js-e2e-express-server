node('jdk11-mvn3.8.4') {
    stage('git') {
        git branch: 'main', url: 'https://github.com/bhargavi-vaduguri/js-e2e-express-server.git'
    }
    stage('build') {
        sh 'npm install'
    } 
    stage('test') {
        sh 'npm test'
    } 
    stage('build') {
        sh 'npm build'
    }
    stage('pack') {
        sh 'npm pack'
    }
}



