# jsp-and-servelets
# Server Log Monitoring System with jsp  
“Super Computing Using Cluster Network” is a vision to achieve super computation speed through the network of simple commercial computers easily available in the market. The amount of data is increasing at a rapid rate and the need to compute these data at faster rate is also high. It deals with the speed and accuracy that is at high demand in sectors that handle large amount of data at a time or for large and complex computation and simulation tasks. With the help of this system the need of high performance at low cost and easy availability has been dealt with. The System is based on self-made distributed architecture without the use of any special libraries. The architecture performs the tasks of job division, handles task queue and result queue, schedules the tasks and supervises the worker nodes. The salient features of our architecture are plug and play software framework, dynamic worker addition and fault tolerance in case of Node failure. These features also make our system reliable for handling large amount of data that needs to be processed at fast rate without error.

The project contains jar files for executing the server for task distribution and and clients as worker to execute the task and an web interface for viewing the log file generated from the jobexecutor server.

Source Monitoring in netbeans:
 Use the link https://github.com/rameskool/jsp-and-servelets.git for cloning it.
 
 Execution:
 
   JRE should be pre-installed.The running operating system should be Windows.
   Apace Tomcat server is essential to run the web interface.
   
 1. Download the project from https://github.com/rameskool/jsp-and-servelets.git in ZIP or open in Desktop .
 2. Extract the zip file.
 3. Run the jar file from /workerfile/ClusterComputing.jar. (To run the jar file folder lib is required) It runs the client which will perform works provided by the server.You can run more than one instant of worker for better performance. (Note: Worker runs in backgroud)
 4. Run the jar file from /starter/ClusterComputing.jar.(To run the jar file folder lib is required).It runs the main server which provides a GUI feature for using the system.
    After starting the jar file from /starter/ClusterComputing.jar , you will see a GUI with two options : For now , only option 1 will work to compute the value of PI. For finding value of PI , you will be asked to enter no. of steps for finding value of PI. More steps will result in more threads and more time.
 
 5. Monitoring from web requires following steps.
    a.Copy the fileprint.war file from /web_interface/dist/ to c:/Xampp/tomcat/webapps.
    b.Open web browser and open localhost:8080/fileprint
    c.Login using username:kool password:hunter    

# Information about cluster:
 All the informations , design patterns and usuage is contained in a pptx file named SuperComputingJournal.pptx above.
