pipeline {

stages {
    stage('unit'){
        agent {
            dockerfile {
                label 'docker-agent-1'
                filename 'Dockerfile'
                dir 'docker'
            }
        }
        steps {
            sh 'npm test'
        }
    }

}

}
