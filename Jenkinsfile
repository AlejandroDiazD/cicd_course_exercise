pipeline {
    agent any

    environment {
        greeting = ''
    }

    stages {
        stage('Assign Greeting') {
            steps {
                script {
                    greeting = 'Hello World'
                }
            }
        }

        stage('Print Greeting') {
            steps {
                script {
                    println(greeting)
                }
            }
        }
    }
}
