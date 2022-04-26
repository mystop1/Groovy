node('64'){
   stage('source'){
      git 'https://github.com/mystop1/Groovy.git' 
   }
   stage ('Compile'){
      sh "gradle clean compliejava test"
   }
}
