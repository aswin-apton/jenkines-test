pipeline{
agent any
stages 
{
stage('Build') 
{
steps{
    git credentialsId: 'github-token-key', url: 'https://github.com/aswin-apton/jenkines-test.git'
echo "Building the Code.........."
}
}
stage('Test') 
{
steps{
echo "Testing the Code.........."
}
}
stage('Compile') 
{
steps{
echo "Compiling the Project.........."
}
}
stage('Deploy') 
{
steps{
echo "Deploying the Project.........."
}
}
}
}