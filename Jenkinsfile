 pipeline {
    agent none
    stages {
        stage('Build') {
            steps {
                sh 'cd /home'
		sh 'rm -rf simple-python-pyinstaller-app.tar.gz'
                sh 'tar -czvf simple-python-pyinstaller-app.tar.gz simple-python-pyinstaller-app'
            }
        }
    }
}
