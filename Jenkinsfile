pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Choisissez la commande en fonction de votre script
                    sh 'pip3 install pandas' // Installer les dépendances
                    sh 'python3 data_analysis.py' // Exécuter le script Python
                }
            }
        }
    }
}
