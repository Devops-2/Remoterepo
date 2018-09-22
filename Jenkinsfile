node ('aws') {
   stage('Checkout') {
       checkout scm
   }
   stage('Build') {
       echo "Building the project"
   }
   stage('Test') {
       echo " testing the project"
       
}
  stage("Calling maven job")
{
echo "calling Mavenfirst repo job"
build 'first-org/mavenfirst/develop'
}
}
