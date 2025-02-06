@Library('jenkins-shared-library') _ // _ means calling library

def configmap= [
    project: "expense"
    component: "backend"
]
if( ! env.BRANCH_NAME.equalIgnoreCase('main')){ // true, if branch is feature branch
    nodeJSEKSPipeline(configMap)
}
else{
    echo "Follow the process to PROD"
}
