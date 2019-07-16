 pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'rm -rf simple-python-pyinstaller-app.tar.gz'
                sh 'git -C /home/simple-python-pyinstaller-app pull'
                sh 'tar -zcvf simple-python-pyinstaller-app.tar.gz /home/simple-python-pyinstaller-app'
            }
        }
        stage('SSH') {
            steps {
                sh "scp simple-python-pyinstaller-app.tar.gz jenkins@192.168.32.3:/home/jenkins/data"

            }
        }
    }
}
