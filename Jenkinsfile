pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Replace with your actual Git repository URL, branch, and credentials
                git(url: 'https://github.com/ukhanna22/DevopsLabExam.git', branch: 'exam-branch')
            }
        }

        stage('Run Shell Script') {
            steps {
                sh './build.sh' // Replace with the actual path to your shell script
            }
        }
    }
}
