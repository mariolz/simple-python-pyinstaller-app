 pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'rm -rf simple-python-pyinstaller-app.tar.gz'
                sh 'cd simple-python-pyinstaller-app'
                sh 'pwd'
                sh 'cd ../'
                sh 'pwd'
                sh 'tar -zcvf simple-python-pyinstaller-app.tar.gz /home/simple-python-pyinstaller-app'
            }
        }
    }
}
