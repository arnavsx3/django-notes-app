@Library('my-shared-library') _

pipeline {

    agent any

    stages {

        stage("Code") {
            steps {
                code()
            }
        }

        stage("Build") {
            steps {
                buildDocker()
            }
        }

        stage("Test") {
            steps {
                test()
            }
        }

        stage("Deploy") {
            steps {
                deploy()
            }
        }

    }
}
