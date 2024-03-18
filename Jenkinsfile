pipeline {
    agent none

    stages {
      
      stage(build) {
        steps {
            echo "This is build stage"
            mkdir test1
            ls ltr
        }
      }

      stage(test) {
        steps {
            echo "this is test stage"
        }

      }

     stage(deploy) {
        steps {
            echo "this is deployment stage"
        }

     }
    
    }
}
