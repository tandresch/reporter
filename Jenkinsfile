podTemplate {
  node(POD_LABEL) {
         stage('Test echo') {
		  sh 'echo "Hallo Thomas"'
		  checkout scm
		  sh 'find . ; echo $?'
		  
       }
  }
} 