
node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/jglick/simple-maven-project-with-tests.git'
    }
   stage('Build') {
      // Run the maven build
     echo "Building from GIT..."
     bat 'start cmd.exe /c C:\\Program Files (x86)\\Jenkins\\workspace\\batchfile.bat'
   }
   stage('Results') {
     echo "Result from GIT......"
     build job: 'gitpull'
   }
}
