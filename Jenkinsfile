pipeline {
    agent any
    parameters {
      string defaultValue: 'prams', description: 'choose environment', name: 'env'
    }

    stages {
        stage('feature') {
            when {
                branch 'feature'
            }
            steps {
                echo'deploy in feature'
            }
        }
        stage('devlop') {
            when {
                branch 'devlop'
            }
            steps {
                echo'deploy in devlop'
            }
        }
        stage('main') {
            when {
                branch 'main'
            }
            steps {
                echo'deploy in main'
            }
        }
    }    
}
