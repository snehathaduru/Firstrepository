node('master'){
    
def a = "this is sneha's laptop"
stage('Checkout') {
    //git 'https://github.com/snehathaduru/Firstrepository.git'
    echo "${BUILD_NUMBER}"
    echo "job name is ${JOB_NAME}"
    
    echo "${a}"
}
stage('Build and Test') {
    echo "${a}"
   env.var1 = "variable had been globalized successfully"
}
stage('Generate Report') {
    echo "${env.var1}"
}

}
