pipeline {
    agent any

    stages {
        stage('file-kiwi1.sql') {
            steps {
                script {
                    // Execute psql command for Stage 1
                    sh "psql -U username -d dbname -f file-kiwi1.sql"
                }
            }
        }

        stage('file-kiwi2.sql') {
            steps {
                script {
                    // Execute psql command for Stage 2
                    sh "psql -U username -d dbname -f file-kiwi2.sql"
                }
            }
        }

        stage('file-kiwi3.sql') {
            steps {
                script {
                    // Execute psql command for Stage 3
                    sh "psql -U username -d dbname -f file-kiwi3.sql"
                }
            }
        }
    }
}