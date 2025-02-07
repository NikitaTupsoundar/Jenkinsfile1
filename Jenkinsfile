Pipeline
{
    agent any
    tools
    {
        maven 'MAVEN_HOME'
    }
    stages
    {
        stage ('Welcome stage')
        {
            steps
            {
                echo 'Welcome to jenkins pipeline'
            }
        }
        stage ('clean stage')
        {
            steps
            {
                bat 'mvn clean'
            }
        }
        stage ('final stage')
        {
            steps
            {
                echo 'final stage'
            }
        }
    }
}