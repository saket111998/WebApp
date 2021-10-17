# WebApp

#Deploying Webapplication using jenkins on Aws instance
#step1
#create the repository 
#and code the application with using normal HTML code 
#build the image of index.html using dockerfile 
 
#step2
#after building image make the tar file of that image and load into aws instance for deployment    
#pipeline process in jenkins will be:
#(job1)fetch-code ---> (job2)Build-image ----> (job3)execute-container(on aws)
#and open the port for 80 in AWS using edit inbound rules in security section of instances  
  
