pipeline {
agent any
stages {
    stage('unit'){
        agent {
            dockerfile {
                filename 'docker/Dockerfile'
            }
        }
        steps {
            sh 'npm test'
        }
    }
}
}
