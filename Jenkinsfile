 pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'cd /home/mario'
                sh 'rm -rf  simple-python-pyinstaller-app.tar.gz'
                sh 'tar -cvzf simple-python-pyinstaller-app.tar.gz simple-python-pyinstaller-app'
            }
        }
    }
}
