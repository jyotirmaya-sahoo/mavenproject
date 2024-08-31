@Library('mylibrary')_
pipeline
{
    agent any
    stages
    {
        stage('continuousdownload')
        {
            steps
            {
                script
                {
                    cicd.gitdownload("maven")
                }
            }
        }
    }
}
