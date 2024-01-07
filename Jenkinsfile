node{
    stage('Clone'){
        git 'https://github.com/jhassam/jenkins-helooworld.git'
    } 
    stage('Build'){
        sh label: 'compile', script: 'javac Main.java'
    }  
    stage('Run'){
        sh label: 'run', script: 'java Main'
    }
} 