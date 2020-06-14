pipeline
{
    agent any
    stages
    {
        stage('Compile')
        {
            steps
            {
                echo 'Hi, This is Bhaskar'
            }
        }
        stage('Unit test')
        {
            steps
            {
                sh './gradlew test'
            }
        }
    }
}