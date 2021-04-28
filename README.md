# Auto-Ecole
Auto Ecole Project


## Requirements


### Data

<details open="open">
   <ul>
      <li><a href="https://www.postgresql.org/">PostgresSQL</a> - Open-Source Relational Database Management System</li>
      <li><a href="https://flywaydb.org/">Flyway</a> - Version control for database</li>
   </ul>
</details>

### Server 

<details open="open">
   <ul>
      <li><a href="http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html">JDK</a> - Java™ Platform, Standard Edition Development Kit</li>
      <li><a href="https://spring.io/projects/spring-boot">Spring Boot</a> - Framework to ease the bootstrapping and development of new Spring Applications</li>
      <li><a href="https://spring.io/projects/spring-boot">Hibernate</a> - Hibernate takes care of the mapping from Java classes to database tables (and from Java data types to SQL data types) and it provides data query and retrieval facilities.</li>
      <li><a href="https://maven.apache.org/">Maven</a> - Dependency Management</li>
   </ul>
</details>

###  Libraries, module and Plugins

<details open="open">
   <ul>
      <li><a href="https://github.com/ultraq/thymeleaf-layout-dialect">Spring Data</a> - Spring Data module is to provide a familiar and consistent, Spring-based programming model for data access while still retaining the special traits of the underlying data store.</li>
      <li><a href="https://projectlombok.org/">Lombok</a> - Never write another getter or equals method again, with one annotation your class has a fully featured builder,    Automate your logging variables, and much more.</li>
	   Spring Data REST: is also used to export Spring Data repositories as hypermedia-driven RESTful resources with a easy way.
      <li><a href="https://swagger.io/">Swagger</a> - Open-Source software framework backed by a large ecosystem of tools that helps developers design, build, document, and     consume RESTful Web services.</li>
   </ul>
</details>

## Installing and setup instructions


### 1. Setup up your app
* 	URL to access application: **http://localhost:8080/**.

* **application.properties** file to data base and jpa setup.
* You need to have **PostgesSQL** installed on your machine to run the application in **`dev`** profile. Using the `PgAdmin` or on any other Postgres client/console, create a database/schema named `auto_ecole`. 

Other Setting : lombok setting

* **To be able to use lombok with Eclipse IDE you must :
* Download Lombok Jar File
* Add lombok dependency in pom.xml
* Run command line

 ```shell 
 $ mvn clean install
 ```
* Once the jar downloaded in Local repository, goto the jar location from the command prompt and run the following command java -jar lombok-1.18.16.jar and we should be greeted by Lombok installation window provided by Lombok
*  Click on the “Specify Location” button and locate the eclipse.exe path under eclipse installation folder.
*  Then you need to finally install this by clicking the “Install/Update” button and you should finished installing lombok in eclipse to be ready to use it.



#### 2. Running the application with IDE

To run the application on your local machine. You must execute the `main` method in the `com.sid.autoEcole.AutoEcoleApplication` class from your IDE.

* 	Download the zip or clone the Git repository.
* 	Unzip the zip file (if you downloaded one)
* 	Open Command Prompt and Change directory (cd) to folder containing pom.xml
* 	Open Eclipse or Intellij
	* File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
	* Select the project
* 	Choose the Spring Boot Application file (search for @SpringBootApplication)
* 	Right Click on the file and Run as Java Application

#### Running the application with Maven


```shell
$ gh repo clone saife04/Auto-Ecole
$ cd Auto-Ecole
$ mvn spring-boot:run
```



### 2. Get your env

```
npm run init
```
Copy the line this script outputs and put it in your `.env` file.

### 4. Setup the demo data

Now we need to run the previous command again and this time it will preload your app with the sample data.

```
npx react-native run-android
```

### 5. Start your app

```
npx react-native start
```

Follow the instructions from the terminal to preview the app on your phone or using an emulator.
### 6. docs

 folder docs / index.html you find all class and function
```
npx  run docs
```
