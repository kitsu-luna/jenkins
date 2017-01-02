#!groovy
node {
  stage('Build') {
    echo "From develop this is Build"
   
  }
  stage('Test') {
    echo "From develop This is Test"
  }
  stage('Deploy') {
    if (currentBuild.result == "SUCCESS") {
      echo "From develop this is Deploy"
    }
  }
}
