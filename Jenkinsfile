pipeline{
   agent any
   stages{
      stage('build'){
         steps{
            bat 'docker build -t my-node-app .'
         }
      }
      stage('run'){
         steps{
          echo 'runing'
         }
      }
       stage('deploy'){
         steps{
          echo 'deploying'
         }
      }
   }
}
      
