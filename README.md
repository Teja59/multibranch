node {

       stage('continuousdownload-master') { 
      
                                                   git 'https://github.com/Teja59/myweb.git'
                                           }    
      stage('continuousbuild-master') {
                                     sh 'mvn package'
                                } 
                                }
