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
                echo'depioy in Dev environment'
            }
        }
    }
}
