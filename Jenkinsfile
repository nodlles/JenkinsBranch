pipeline{
    agent {
        node{
            label "test"
        }
    }
    stages {
        stage("测试内容"){
            steps {
                script {
                    bat label: "echo sth", script: """
                    cd
                    """
                }
            }
        }
    }
}
