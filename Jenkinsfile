stage('Install Dependencies') {
    steps {
        sh 'npm install'
    }
}

stage('Build') {
    steps {
        sh 'npm run build'
    }
}

stage('Automated Testing') {
    steps {
        sh 'npm test'
    }
}