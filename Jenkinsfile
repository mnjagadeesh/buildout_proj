pipeline{
    agent {any}
    options {
            timeout(time: 1, unit: "HOURS")
            retry(3)
    }

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
