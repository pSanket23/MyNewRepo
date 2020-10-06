node('master'){
  stage('Stage1'){
              echo "Building nothing!!!!"
  }
  
  stage('Stage2'){
              echo "Building nothing!!!!"
  }
  
  stage('Clone repo'){
              echo "cloning repo!!!!"
              checkout scm
  }
  
  stage('Copy Sanket'){
              sh 'mkdir temp'
              sh 'cp Sanket temp/'
  }
 }

node("test"){
  stage('Clone repo'){
              echo "cloning repo!!!!"
              checkout scm
  }
  
  
}
    
    
    
