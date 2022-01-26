podTemplate {
  node(POD_LABEL) {
         stage('Test echo') {
		  scm checkout 
		  sh 'echo "Hallo Thomas"'
          sh 'find . ; echo $?'
       }
  }
} 