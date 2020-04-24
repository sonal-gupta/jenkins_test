pipeline{

    agent any
    options
    {
        timestamps()
        ansiColor("xterm")
    }
    stages {
        stage('stage1')
        {
            options
                {
                    timeout(time :1, unit: "MINUTES")
                }
            steps {
                sh "printf executing step 1"
            }
        }
        stage('stage2')
        {
           options
                {
                    timeout(time :2, unit: "MINUTES")
                }
            steps {
                sh "printf executing step 2"
            }
        }
    }
    

}
