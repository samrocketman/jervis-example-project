#!groovy
//Global pipeline library located at https://github.com/samrocketman/jervis
//depends on .jervis.yml
buildViaJervis()
pipeline {
    agent {
        label 'ubuntu1604'
    }
    stages {
        stage('Simulated deploy') {
            when { branch 'master' }
            steps {
                sh 'env | LC_ALL=C sort'
                unstash 'artifacts'
                unstash 'cobertura'
                unstash 'junit'
                sh 'find . -type f'
            }
        }
    }
}
