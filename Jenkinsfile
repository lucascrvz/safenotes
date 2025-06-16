pipeline {
    agent any
    stages {
        stage('Dependency Check') {
        steps {
            sh './dependency-check/bin/dependency-check.sh --scan . --format HTML --out reports/'
        }
    }
    }
}