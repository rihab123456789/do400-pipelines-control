node('nodejs'){
    stage('Checkout'){
        git branch: 'main',\
            url: 'https://github.com/rihab123456789/do400-pipelines-control.git'    }
    stage('Backend Tests'){
        sh 'node ./backend/test.js'
    } 
    stage('Frontend Tests'){
        sh 'node ./frontend/test.js'
    }
}
