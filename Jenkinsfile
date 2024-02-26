pipeline {
    agent any


    stages {
        stage('git') {
            steps {
                // Get some code from a GitHub repository
                git "https://github.com/Dwaraka224/Feb26_Jenkinsfile.git"

                
                sh "java Demo.java"
                sh "python3 main.py"

                
            }
        }
    }
}

