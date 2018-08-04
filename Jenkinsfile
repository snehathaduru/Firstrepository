node('master'){
    

stage('Checkout') {
    git 'https://github.com/snehathaduru/Firstrepository.git'
}
stage('Build and Test') {
 sh 'ls -ltr'
}
stage('Generate Report') {
    
}
    
 stage('Notification stage'){
       // slackSend channel: 'devops_training', message: 'Hi this is the Devops Training', teamDomain: 'devopsdemoworkspace', token: '1zjBfLfJ9KPbwQNHk9Ivi3Ze'
    }

}
