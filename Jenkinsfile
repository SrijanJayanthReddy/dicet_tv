pipeline {
    agent {label 'dev'}
    tools {maven 'maven'}
    stages 
    {
        stage('git') 
        {
            steps 
            {
                git 'https://github.com/SrijanJayanthReddy/dicet_tv.git'
            }
        }
            stage('maven')
            {
                steps
                {
                    sh 'mvn clean package'
                }
            }
}
    
}
