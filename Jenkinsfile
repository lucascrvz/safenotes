pipeline {
    agent any
    stages {
        stage('Dependency Check') {
            steps {
                sh '../../dependency-check/bin/dependency-check.sh --project "SafeNotes" --scan . --format HTML --out reports/'
            }
        }
    }
}