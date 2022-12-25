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
    }
}
