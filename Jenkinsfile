pipeline {
    agent any

    stages {

        stage('Use Credential') {
            steps {
                withCredentials([
                    string(
                        credentialsId: 'demo-secret',
                        variable: 'MY_SECRET'
                    )
                ]) {
                    echo "Credential is available securely to this stage."
                }
            }
        }
    }
}