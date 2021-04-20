
// Pipeline Declarativo (siempre comienza por pipelina)

pipeline {
    // Ejecutar en cualquier agente (nodo)
    agent any
    // Fases del trabajo
    stages {
        // Fase individual (contenedor logico)
        stage('Build') {
            // Pasos de la fase
            steps {
                echo 'Building...'
            }
        }
        // Fase individual (contenedor logico)
        stage('Test') {
            // Pasos de la fase
            steps {
                echo 'Testing...'
                echo 'Aceptación...'
                echo 'Integración...'
            }
        }
        // Fase individual (contenedor logico)
        stage('Deploy') {
            // Pasos de la fase
            steps {
                echo 'Deploying...'
            }
        }
    }
    
}

