@Library('library') _

import es.yan.Persona
import es.yan.Profesor
import es.yan.Estudiante
import es.aula.Aula

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                script {
                    def person = new es.yan.Person("Yan", "Garcia")

                    person.printName()
                    person.printSecondName()
                    person.crearAula()
                    person.printInstanceOf(new Profesor('Juan', 'Perez', 'Matematicas', '1'))
                    person.printAula()

                }
            }
        }
    }
}