pipeline {
    agent any
    stages {
        stage('Build') 
{
            steps 
{
                echo 'Build the code'
            }
        	}
stage('Test') 
{
            steps 
{
                echo 'Test The Code'
            }
        	}
stage('Deploy') 
{
            steps 
{
                echo 'Deploy the code'
            }
        	}

    }

post
 {
always
{
mail bcc: '', body: 'Summary', cc: '', from: '', replyTo: '', subject: '', to: 'sagarsangale962@gmail.com'
}
}

}
