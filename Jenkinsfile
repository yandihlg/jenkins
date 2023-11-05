@Library('library') _

import es.yan.Persona
import es.yan.Profesor
import es.yan.Estudiante
import es.aula.Aula
import es.utils.Utils

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                script {

                    herencia.person.printName()
                    herencia.person.printSecondName()
                    herencia.person.crearAula()
                    herencia.person.printInstanceOf(new Profesor('Juan', 'Perez', 'Matematicas', 1))
                    herencia.person.printAula()

                    def aula = new Aula()
                    aula.addPersona(new Profesor('Juan', 'Perez', 'Matematicas', 1))
                    println(Utils.printStaticMethod())

                }
            }
        }
    }
}