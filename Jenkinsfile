node('master'){
  stage('Clean Work space'){
              deleteDir()
  }

  
  stage('Clone repo'){
              echo "cloning repo!!!!"
              checkout scm
  }
  
  stage('Copy Sanket'){
              sh 'mkdir temp'
              sh 'touch Sanket.txt'
              sh 'cp Sanket.txt temp/'
  }
 }

node("test"){
  stage('Clean Work space'){
              deleteDir()
  }
  
  stage('Clone repo'){
              echo "cloning repo!!!!"
              checkout scm
  }
  
  
}
    
    
    
