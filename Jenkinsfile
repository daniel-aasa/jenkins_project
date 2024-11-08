pipeline {
    agent any
    stages {
        stage("Clone Git Repository") {
            steps {
                git(
                    url: "https://github.com/daniel-aasa/jenkins_project.git",
                    branch: "master",
                    changelog: true,
                    poll: true
                )
            }
        }
    }
}
