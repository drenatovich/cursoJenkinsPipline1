pipeline {
    stages {
        stage('Compilacion'){
            steps {
                echo 'Voy a compilar:'
                echo 'Estoy en ello.....'
                echo 'Listo'
            }
            post {
                success {
                    echo 'Se ha ejecutado si los steps han ido bien'
                }
                failure {
                    echo 'Se ha ejecutado si los steps han ido mal'
                }
                always {
                    echo 'Se ha ejecutado en cualquier caso'
                }
            }
        }
        stage('Pruebas'){
            steps {
                echo 'Voy a compilar:'
                echo 'Estoy en ello.....'
                echo 'Listo'
            }
            post {
                success {
                    echo 'Se ha ejecutado si los steps han ido bien'
                }
                failure {
                    echo 'Se ha ejecutado si los steps han ido mal'
                }
                always {
                    echo 'Se ha ejecutado en cualquier caso'
                }
            }
        }
    }
    post {
        success {
            echo 'Se ha ejecutado si los steps han ido bien'
        }
        failure {
            echo 'Se ha ejecutado si los steps han ido mal'
        }
    }
}