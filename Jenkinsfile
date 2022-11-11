pipeline{
    agent any

    stages{

        stage('Git checkout'){
            
            steps{
                git branch: 'main', url: 'https://github.com/legenie1/spring_ci_cd.git'
            }
        }
    }
}