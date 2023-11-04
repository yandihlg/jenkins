@Library('library') _
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                script {
                    println("hola" + ' ' + "mundo")
                    def person = callperson(imprimir:"esto es una pinga")
                }
            }
        }
    }
}