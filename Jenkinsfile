pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Running main logic...'
            }
        }
    }
    // Tambahkan bagian ini untuk mendapatkan fitur seperti di gambar
    post { 
        always { 
            echo 'This will always run after the stages.'
        }
        success {
            echo 'The pipeline completed successfully!'
        }
        failure {
            echo 'The pipeline failed.'
        }
        cleanup {
            echo 'Cleaning up resources...'
        }
    }
}
