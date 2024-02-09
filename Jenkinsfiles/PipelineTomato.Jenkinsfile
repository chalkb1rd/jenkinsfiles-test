pipeline {
    agent any

    stages {
        stage('file-tomato1.sql') {
            steps {
                script {
                    // Execute psql command for Stage 1
                    sh "psql -U username -d dbname -f file-tomato1.sql"
                }
            }
        }

        stage('file-tomato2.sql') {
            steps {
                script {
                    // Execute psql command for Stage 2
                    sh "psql -U username -d dbname -f file-tomato2.sql"
                }
            }
        }

        stage('file-tomato3.sql') {
            steps {
                script {
                    // Execute psql command for Stage 3
                    sh "psql -U username -d dbname -f file-tomato3.sql"
                }
            }
        }
    }
}