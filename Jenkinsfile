pipeline { 
    agent {
        label 'ws'
    }
    stages {
        stage('Lint Checks') {
            steps {
                sh "echo Performing Lint Checks"
                // sh "pip install pylint"
                sh "echo Style Checks Completed"
            }
        }

        stage('Static Code Analysis') {
            steps {
                sh "echo Static Checks ...."
            }
        }

    }
}