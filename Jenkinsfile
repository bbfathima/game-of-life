pipeline{
    agent{label 'abc' }
    stages{
        stage(clone) {
            steps{
                git url: 'https://github.com/bbfathima/game-of-life.git',
                    branch: 'declarative'
            }
        }
    }
}
