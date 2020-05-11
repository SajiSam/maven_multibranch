node('master')
{
   stage('ContinuousDownload_masteronSajSam') 
   {
       git 'https://github.com/intelliqittrainings/maven.git'
   }
   stage('ContinuousBuild-Masteronsajsam') 
   {
       sh label: '', script: 'mvn package'
   }
  }
