podTemplate(inheritFrom: 'mypod', containers: [
    containerTemplate(name: 'maven', image: 'maven:3.8.1-jdk-11')
  ]) {
  node(POD_LABEL) {
       stage('build') {
       
	   sh 'mvn --version'

       }
  }
} 