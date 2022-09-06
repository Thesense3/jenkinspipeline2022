pipeline{ 

agent any

stages {
	stage ('SCM') {
		steps {
				echo "git pull codee"
				git "https://github.com/Thesense3/simple-java-maven-app.git"		
			}	
}


	stage ('build') {
		steps {

			  sh "mvn clean package"
		}
}


	stage ('deploy') {
		steps{ 
		
			 sh 'java -jar target/*.jar'
		}
	}

}

}