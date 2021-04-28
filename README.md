# Auto-Ecole
Auto Ecole Project
# sportapp


## Requirements

- NodeJS npm
- React native
- android

## Setup instructions


# Installing

### 1. Setup up your app
* 	URL to access application: **http://localhost:8080/**.

* **application.properties** file to data base and jpa setup.



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
