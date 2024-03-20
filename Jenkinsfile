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
            sh "cat './build.sh'"
        }

      }

     stage(deploy) {
        steps {
            echo "this is deployment stage"
        }

     }
    
    }
}
