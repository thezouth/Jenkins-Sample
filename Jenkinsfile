pipeline {
agent any
stages {
    stage('unit'){
        agent {
            dockerfile {
                label 'docker'
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
