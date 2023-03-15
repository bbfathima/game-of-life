pipeline {
    agent {label 'FATHIMA' }
    stages {
        stage(clone) {
            steps{
                git url: 'https://github.com/bbfathima/game-of-life.git',
                    branch: 'declarative'
            }
        }
        stage(build) {
            steps {
                sh './mvnw package'     
            }
        }
    }
}
