pipeline {
    agent any

    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Build In Progress') {
            steps {
                echo 'Build In Progress'
            }
        }
        stage('Test In Progress') {
            steps {
                echo 'Testing In Progress'
            }
        }   
        stage('Deployment In Progress') {
            steps {
                echo 'Deployment In Progress'
            }
        }           
    }
}
