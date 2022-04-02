pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                docker build -t profed11/devops_proj2:latest .
                docker login -u "profed11" -p "eR-PaE9Evrun7!Z" docker.io
                docker push profed11/devops_proj2:latest
            }
        }
    }
}
