pipeline {
    agent any
    stages {
        stage('build') {
            when{
                buildingTag()
            }
            steps {
                echo "hello world building tag"
            }
        }
    }
}
