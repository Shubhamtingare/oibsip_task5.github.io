How to Run -
1- Install these:
    Java SE Development Kit 8 (JDK 8)
    After installing JDK 8, install NetBeans IDE
2- Open NetBeans IDE. Click on File -> Open Project and browse to the downloaded folder named "Project" and select it. It will load the NetBeans project.

3- Now everything is setup except the Java DB (Derby) Database of NetBeans. So, follow these steps to setup the database:

Step 1: In the Netbeans Window, there is a tab named "Services" on the left. Select it. Then right click on JavaDB > Properties and change database location to "Database" folder downloaded with this repository (its placed besides the "Project" folder).

Step 2: After that a database named LMS will show up under JavaDB tab. Now Right Click Databases > New Connection and select Java DB Network and click Next.

Step 3: Provide the following database crendentials in the next popup and click Next.
      Host: localhost
      Port: 1527
      Database: LMS
      User Name: haris
      Password: 123

Step 4: Now just click Next for the rest of the windows. After all this the database connection is made. Make sure that you connect with the database before running the project by right clicking on the connection and selecting connect. Now you are ready to run the project!
