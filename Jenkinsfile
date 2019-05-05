pipeline {
agent any
stages {
    stage('unit'){
        agent {
            dockerfile {
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
