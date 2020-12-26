pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
		   cp -r /var/jenkins_home/byousefi/.  /var/jenkins_home/workspace/pipeline-byousefi-gateway
		   docker-compose -f docker-compose-build.yml build
		'''
            }
        }
    }
}