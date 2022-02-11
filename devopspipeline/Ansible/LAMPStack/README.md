Step1: run apache role
--> set up tasks/main.yml
--> setup vars/main.yml
--> set up handlers
Step 2: set up yml file to run apache role
lamp.yml is the yml created specifically for the roles. 
lampall.yml has the complete scripts you run w/o creating roles
Step3: set up mysql role 
Step4: add this role to lamp.yml and run it
Step5: set up php role 
Step6: add this role to lamp.yml and run it
Step7: set up wordpress role 
Step8: add this role to lamp.yml and run it
Step9: get the IP of container and test it: IP:port

PS: to create roles do ansible-galaxy apache php mysql wordpress 1 at a time then copy and paste the code to each role.
