pipeline {

agent any


stages {

stage('GIT') {

           steps {

               git branch: 'master',

               url: 'https://github.com/salsabil-27/timesheetproject.git'

          }

     }

stage ('Compile Stage') {

    steps {

        sh 'mvn clean compile'

    }

}

}

}