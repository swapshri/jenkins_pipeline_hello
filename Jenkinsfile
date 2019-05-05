node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
     input "Deploy to dev?"
     input "Deploy to pre-prod?"
     input "Deploy to prod?"
}

node {
    stage('deploy to qa'){
        echo "deploying"
    }
}

node {
    stage('deploy to dev'){
        echo "deploying"
    }
}

node {
    stage('deploy to pre-prod'){
        echo "deploying"
    }
}

node {
    stage('deploy to prod'){
        echo "deploying"
    }
}
