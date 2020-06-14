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
                sh 'gradle build'
            }
        }
         stage('Help')
         {
            steps
            {
                sh 'gradle help'
            }
         }
    }
}