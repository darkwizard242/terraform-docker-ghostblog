node {
   stage('Checkout Terraform code') {
      git 'https://github.com/Tech-Overlord/terraform-docker-ghostblog.git'
   }
   stage('Terraform version') {
     steps {  
       sh 'terraform -version' }
   }
}
