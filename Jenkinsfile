pipeline {
    agent any

    stages {
      
      stage(build) {
        steps {
            echo "This is build stage"
            sh "chmod +x './build.sh' "
            sh './build.sh'
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
