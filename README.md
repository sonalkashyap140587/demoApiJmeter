# demoApiJmeter
Performance Testing:
1. I have set up a project in Jmeter using POST, GET, PUT & DELETE operations.
2. Added listeners like View Result Tree and Summary Report to check the performance factors.
3. Create a job in jenkins using same .jmx file and added performance trends.
4. The attached demo videos can be referred more details.

Configuration in Jmeter:
1. Confgigure POST, GET, PUT & DELETE api in jmeter using https://gorest.co.in/ .
2. Add listeners like View Result Tree and Summary Report for the performance factors.
3. A unique id will be generated after running POST operation and that can be used for all other operations.
4. Also run the GET operation again to check if that id is availble or not.
6. Run the thread and check all the reports accordingly.

Configuration in Jenkins:
1. Create a freestyle job in jenkins and configure the path where project(.jmx file) is saved in local.
2. Add the command for running .jmx file using jenkins in excecute windows batch commands.
3. Add Performance Trends using .jtl for the same project which can also be verified in jenkins.
4. Save the configuration.
7. Make sure that environment variables for Java JDK and Jmeter is set accordingly.
8. Run the job and observe the results in console which shows the summary and also the check the performance trends(screenshots also attached for reference)
