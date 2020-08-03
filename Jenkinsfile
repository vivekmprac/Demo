pipeline {
    agent any
    stages {
        stage('build') {
            when {
                changelog '.*some_text.*'
            }
            steps {
                echo "hello world change log"
            }
        }
    }
}
