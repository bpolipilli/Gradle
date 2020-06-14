pipeline
{
    agent any
    stages
    {
        stage('Input Message')
        {
            steps
            {
                echo 'Hi, This is Bhaskar'
            }
        }
        stage('Build')
        {
            steps
            {
                sh './gradlew build'
            }
        }
         stage('Help')
         {
            steps
            {
                sh './gradlew help'
            }
         }
    }
}