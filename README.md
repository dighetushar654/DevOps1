# DevOps1


Step 1: Open your Git bash and create two branches at developers one is master &
Developer1


Step 2: Push on the Git hub on your repository of your account.

Step 3:Open your terminal in your Redhat. Start Jenkins and Docker using these commands:
systemctl start jenkins 
systemctl enable jenkins 
systemctl start docker
Step 4: Open Jenkins on your specified port. Click on New Item to create a Job.
 
Step 5: Select a freestyle project and provide the item name (here I have given Job1) and click OK.                        
Step 6: Select Source Code Management and provide the Git repository. Click on Apply and Save button.
                                                                                

Step 7: Then click on Build->Select Execute Shell. 

Step 8: Configure the job1(Dev1) Keep on checking the dev1 code & create the docker container 8081:80 port to testing the code. 

Step 9: create the Job2(Master Branch)
                                                                                
Step 10: Job2 (Master Branch) Keep on checking the original developer code & create the docker container 8082:80 port to run the production web server to access the clients.
                                                                                
Step 11: Create the Job3(QAT) to merge the Dev1 & Master branch data.
                                                                                
Step 10: Redhat terminal after job1 & job 2 Running the Two container is Runs.

Step 11: job 3 Gives the confirmation to code is ok, you can merge it.
                                                                                
Step 12: Jobs On Jenkins.....
                                                                                    

Step 13: Master branch Simple HTML code:

Step 14: Developer 1 Branch added the CSS code:

Step 12: job3 Merge the master & Developer 1 So.........

Step 12: Same Output Generate on production site
