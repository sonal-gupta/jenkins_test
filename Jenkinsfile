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
                     sh 'printf "\\e[31mexecuting step1\\e[0m\\n"'
            }
        }
        stage('stage2')
        {
           options
                {
                    timeout(time :2, unit: "MINUTES")
                }
            steps {
                     sh 'printf "\\e[31mexecuting step2\\e[0m\\n"'
            }
        }
    }
    

}
