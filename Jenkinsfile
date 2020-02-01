

node('master') {
    checkout scm

stage('build') {
    withMaven(jdk: 'jdk8', maven: 'mvn') {
    sh label: '', script: 'mvn clean install'
}
}}
