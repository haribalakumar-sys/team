pipeline{
    agent any
        stages{
            stage('java compile')
            {
                steps
                {
                    bat 'javac hari.java'
                }
            }
            stage('run')
            {
                steps{
                   bat 'java hari'
                }
            }
        }
    
}