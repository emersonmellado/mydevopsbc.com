pipeline {
    agent any
    node('dell-rig'){
        stages {
            stage('Build') {
                steps {
                    sh 'echo "Deploying to eb"'
                    sh 'eb init -p python-3.6 mydevopsbc --region us-west-2 --profile erm'
                    sh 'eb deploy --profile erm'
                }
            }
        }
    }
}
