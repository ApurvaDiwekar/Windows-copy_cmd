pipeline {
    agent any
    
    stages {
        stage('Copy Files') {
            steps {
                // Copy files from source directory to destination directory
                bat 'xcopy /s /e /y "C:\\Users\\Apurva\\Desktop\\New vision resume dmato added" "C:\\Users\\Apurva\\Desktop\\Aprill naukri 2"'
            }
        }
    }
    
    post {
        success {
            echo 'Files copied successfully!'
        }
        failure {
            echo 'Failed to copy files!'
        }
    }
}
