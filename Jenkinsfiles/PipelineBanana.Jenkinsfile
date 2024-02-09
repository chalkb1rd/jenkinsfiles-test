pipeline {
    agent any

    stages {
        stage('file-banana1.sql') {
            steps {
                script {
                    // Execute psql command for Stage 1
                    sh "psql -U username -d dbname -f file-banana1.sql"
                }
            }
        }

        stage('file-banana2.sql') {
            steps {
                script {
                    // Execute psql command for Stage 2
                    sh "psql -U username -d dbname -f file-banana2.sql"
                }
            }
        }

        stage('file-banana3.sql') {
            steps {
                script {
                    // Execute psql command for Stage 3
                    sh "psql -U username -d dbname -f file-banana3.sql"
                }
            }
        }
    }
}