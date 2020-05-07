pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
             steps {
                  withAWS(region:'us-west-2', credentials:'AKIA4FY3QZRSRQHFHSXX') 
{
            s3Upload(file:'index.html', bucket:'jenkinspipelineonaws')


             }
         }
     }
    }
}