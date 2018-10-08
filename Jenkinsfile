// This shows a simple build wrapper example, using the Timestamper plugin.
node {
    stage('Build') { 
        echo 'THIS IS FIRST STAGE'
	sleep 5
	echo 'CODE IS COMPILED' 
    }
    stage('Test') {
	timestamps {
        	stage "First echo"
        	echo "Hey, look, I'm echoing with a timestamp!"

	        stage "Sleeping"
        	sleep 30

 	       	stage "Second echo"
        	echo "Wonder what time it is now?"
    	}
        
	echo 'TEST IS COMPLETED'
    }
    stage('Deploy') {
        echo 'CODE READY FOR NEW USE'
    }

}

