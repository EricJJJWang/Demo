pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Remove folder') { 
            steps { 
                echo 'Remove folder'
                sh 'rm -rf Demo'
            }
        }
        stage('Git Clone') { 
            steps { 
                echo 'Git Clone'
                sh 'git clone https://github.com/EricJJJWang/Demo.git'
            }
        }
        
    }
}
