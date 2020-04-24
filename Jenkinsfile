pipeline {
        agent any
        stages {
                stage('stage1') {
                        steps {
                                echo 'This is normal stage'
                        }
                }
        }
        post {
                Failure {
                        echo 'This is post build step'
                }
        }
}
