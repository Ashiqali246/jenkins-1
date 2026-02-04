pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('git-checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Ashiqali246/demo.git'
            }
        }
    }
}
