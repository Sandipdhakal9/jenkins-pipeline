pipeline{
    agent{
        label "any"
    }
    stages{
        stage("build"){
            steps{
                echo "========executing A========"
            }
            post{
                always{
                    echo "========always========"
                }
                success{
                    echo "========A executed successfully========"
                }
                failure{
                    echo "========A execution failed========"
                }
            }
        }
        stage("test"){
            steps{
                echo "========Testing A========"
            }
            post{
                always{
                    echo "========always========"
                }
                success{
                    echo "========A  test executed successfully========"
                }
                failure{
                    echo "========A test execution failed========"
                }
            }
        }
        stage("deploy"){
            steps{
                echo "========deploy executing A========"
            }
            post{
                always{
                    echo "========always========"
                }
                success{
                    echo "========A deploy executed successfully========"
                }
                failure{
                    echo "========A deploy execution failed========"
                }
            }
        }
    }
}
