pipeline{
    agent any
    stages{

    stage('Deploy - Staging') {
    steps {
        sh 'echo ./deploy staging'
        sh 'echo ./run-smoke-tests'
    }
}
stage('Deploy - Production') {
    steps {
        sh 'echo ./deploy production'
    }
}
}
}
