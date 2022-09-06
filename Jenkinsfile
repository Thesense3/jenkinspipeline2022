pipeline{ 

agent any

stages {
	stage ('SCM') {
		steps {
				echo "git pull code"
				git "https://github.com/Thesense3/simple-java-maven-app.git"		
			}	
}


	stage ('build') {
		steps {

			  sh 'mvn clean package'
		}
}


	stage ('Test now') {
		steps{ 
		
			echo "test code it is"
		}
	}

}

}