 pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'cd /home'
                sh 'pwd'
                sh 'tar -zcvf simple-python-pyinstaller-app.tar.gz /home/simple-python-pyinstaller-app'
            }
        }
    }
}
