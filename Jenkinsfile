pipeline {
    agent any
    
    stages {
        stage("Compilation") {
            steps {
                script {
                    sh "./gradlew compileJava"
                }
            }
        }
        
        stage("Test unitaire") {
            steps {
                script {
                    sh "./gradlew test"
                }
            }
        }
        
        // Vous pouvez ajouter d'autres étapes de déploiement ou de vérification ici
    }
    
    // Vous pouvez également ajouter des directives post-build, notifications, etc.
}

