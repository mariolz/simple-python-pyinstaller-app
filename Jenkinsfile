 pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'rm -rf simple-python-pyinstaller-app.tar.gz'
                sh 'git clone https://github.com/mariolz/simple-python-pyinstaller-app.git'
                sh 'tar -zcvf simple-python-pyinstaller-app.tar.gz /home/simple-python-pyinstaller-app'
                sh 'rm -rf simple-python-pyinstaller-app'
            }
        }
        stage('Deliver') {
            steps {
                sh 'scp'
            }
        }
    }
}
