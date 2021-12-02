// install ansi plugin
/*node {
    ansiColor('xterm') {
        stage "\u001B[31mI'm Red\u001B[0m Now not!!"
    }
}
*/

pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
