pipeline{



agent any

stages{

stage('build'){

steps{echo "this is the build job"}

bat "mvn clean"
}

stage('deploy'){
step{
echo "this is the deploy job"
bat "mvn deploy"
}

}

stage('test'){
steps{
echo "this is the test job"
bat "mvn test"
}

}

stage('release'){
steps{echo "this is the release job"}

}

}



}
