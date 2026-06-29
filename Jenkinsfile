pipeline {
    agent any


    stages {

        stage('rebuild pipelines') {
            steps {
                script {
                    sh 'curl -X POST \
  https://github-jenkins.ninja/job/shangal-pipe/build \
  --user mohammad:1187bdf6a2a4bc500693bad54e4e2f2afa'

                    sh 'curl -X POST \
  https://github-jenkins.ninja/job/mangal-pipe/build \
  --user mohammad:1187bdf6a2a4bc500693bad54e4e2f2afa'
                }
            }
        }

        
}
}
