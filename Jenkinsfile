pipeline {
    agent any
    parameters {
      string defaultValue: 'prams', description: 'choose environment', name: 'env'
    }

    stages {
        stage('Dev') {
            when {
                expression {prams.env=="Dev"}
            }
            steps {
                echo'deploy in Dev environment'
            }
        }
        stage('test') {
            when {
                expression {prams.env=="test"}
            }
            steps {
                echo'deploy in test environment'
            }
        }
    }
}
