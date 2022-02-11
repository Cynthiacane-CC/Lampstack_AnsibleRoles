Step1: run apache role
--> setup meta/main.yml: add your name description and company.
--> setup tasks/main.yml.
--> setup vars/main.yml.
--> setup handlers.

Step 2: set up yml file to run apache role.
lamp.yml is the yml created specifically for the roles. 
lampall.yml has the complete scripts you run w/o creating roles

Step3: set up firewall role.
Step4: add this role to lamp.yml and run it.

Step5: set up mysql role.
Step6: add this role to lamp.yml and run it.

Step7: set up php role.
Step8: add this role to lamp.yml and run it.

Step9: set up wordpress role.
Step10: add this role to lamp.yml and run it.

Step11: get the IP of container and test it: IP_Host:port.

Step12: check the logs (config log, acces_log, error_log if you can't access website on browser by login in to your container).

PS: to create roles do ansible-galaxy apache php mysql wordpress 1 at a time then copy and paste the code to each role.
