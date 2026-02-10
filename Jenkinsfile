pipeline {
    agent any

    stages {
        stage('Load Groovy') {
            steps {
                script {
                    def h = load 'hello.groovy'
                    h.call()
                }
            }
        }
    }
}
