### Exercise 2: Problem solving case

This File build based on JAVA 11 and maven 3.8.3 , please make sure you have maven in your local pc <br/>

### Build & Run JUnit Test
Use the below command on terminal to create jar file and run JUnit test
```bash
mvn clean install
```

To Skip test and build jar file only type below command:
```bash
mvn clean install -Dmavnen.test.skip=true
```

### Run Application
Go to JAR directory and run the below command 
 ```bash
 java -jar Exercise-two-1.0-jar-with-dependencies.jar
```
The app asked the file , type file name or profile full path to your file 
<b>order_log00.csv</b>

The application will  generate two output file in the same  order_log00 file directory:<br/>
~/jar/0_order_log00.csv<br/>
~/jar/1_order_log00.csv<br/>


