pipeline{
    agent any
    stages{
        stage('Build'){
            steps {
                  echo "Clean non git controlled files"
                  git clean -fdx
            }
        }
        stage('Run Buildout'){
            steps {
                  echo "Clean non git controlled files"
                  /home/mnjagadeesh/ve3/bin/buildout -n
            }
        }
    }
}
