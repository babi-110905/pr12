pipeline {
    agent any
    stages {
        stage('Build') { steps { bat 'javac RecipeFinder.java' } }
        stage('Run') { steps { bat 'java RecipeFinder' } }
    }
}
