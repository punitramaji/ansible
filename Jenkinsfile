pipeline {
    agent any
    stages{
      stage ("checkout") {
        steps {
          echo 'checkout source code'
          git 'https://github.com/punitramaji/ecommerce-demo.git'
        }
      }
      stage ("build") {
        steps {
          echo 'checkout source code'
        }
      }
      stage ("test") {
        steps {
          echo 'checkout source code'
        }
      }
      stage ("deploy") {
        steps {
          echo 'checkout source code'
          sh 'sudo ./install.sh'
        }
      }
    }
}
