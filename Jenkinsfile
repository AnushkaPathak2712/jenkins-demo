pipeline{
  agent any 
  stages{
    stage('Checkout'){
      steps{
        git 'https://github.com/AnushkaPathak2712/jenkins-demo.git'
      }
    }
    stage('Publish'){
      steps{
        publishHTML([
          allowmissing:true,
          alwaysLinktoLastBuild:false,
          KeepAll:false,
          reportDir:'.',
          reportFiles: 'sample.html'
          reportName:'MY HTML PAGE'
          )]
                    }
                    }
                    }
    
