pipeline {
       // agent any
	agent {
        docker {
            image 'maven:3-alpine'
          //  args '-v $HOME/.m2:/root/.m2'
        }
       }
        stages {
         stage(build) {
                steps{
                 echo "build"
                     }
		}
         stage(test) {
                steps{
                 echo "build"
                     }
		}
	}
}
