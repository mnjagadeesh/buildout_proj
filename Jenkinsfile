pipeline{
    agent any
    stages{
        stage('Build'){
            steps {
                  echo "Clean non git controlled files"
                  sh "git clean -fdx"
            }
        }
        stage('Run Buildout'){
            steps {
                  echo "Clean non git controlled files"
                  sh "/home/mnjagadeesh/ve3/bin/buildout -n"
            }
        }
    }
}
