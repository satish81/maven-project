
Pipeline {
    agent any
    stage ( "Initialize" ) {
        steps {
            sh '''
                echo "PATH = $PATH"
                echo "M2_HOME = $M2_HOME"
            '''
            }
        }
        
        stage { "Build" } {
            steps {
                echo "Hello world!"
            }
        }
   }
 }  
   
