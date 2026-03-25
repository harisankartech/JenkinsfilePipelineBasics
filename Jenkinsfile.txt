pipeline{

 agent any

 stages{

stage('Develop'){
  
  stage{
    echo "Developing the system"
  }
  
}

stage('Test'){
  stage{
    echo "Testing the system"
  }
  
}
stage('Deploy'){
  steps{
    echo "Deploy the system"
  }
}

}

}