## MIT S011: FINAL DELIVERABLE

_Course Overview_:

 * Essential elements of web page development, covering:
 	* HTML,
 	* CSS and
 	* JavaScript
 * Front-end development using the following: 	
 	* Bootstrap
 	* NodeJS
 	* AngularJS
 	* MVC Design Pattern
 * Back-end support
 	* NodeJS
 	* AngularJS
 	* Express
 	* MySQL
 * Full Stack Web Development
 	* Server-side application (CRUD and REST)
 	* Build and configure a backend server

_Task_

>Using the _phonecatApp_ activity, create a server side application that will provide an ```UPDATE``` to the phone information.


_Submission Details: Deliverables_

 * Create new repo ```FullStack_PhoneCatApp```.
 * Push all your fullstack phonecat app files.
 * Include a schema diagram of your phonecat database.
 * Include a DDL Create SQL Script ```phonecatapp.sql``` (if you decide to use NoSQL Database such as CouchDB, Cassandra, MonggoDB, etc. that is still accepted).
 * Using your new repo _README_ markdown file ```README.md```, briefly discuss the concept of your PhoneCat application full stack development. This includes front-end and back-end tools that support your development. And lastly, discuss the highlights of the development such as ```MVC and SQL scripts``` and the like.
 * Deadline of submission: August 14, 2016.

_Task Matrix_

##Submited Final Project
##Kevin John A. Rivera

## Prerequisites

### Git

- A good place to learn about setting up git is [here][git-setup].
- You can find documentation and download git [here][git-home].

### Node.js and Tools

- Get [Node.js][node-download].
- Install the tool dependencies: `npm install`

### XAMPP / WAMP 
>(if you decide to use NoSQL Database such as CouchDB, Cassandra, MonggoDB, etc. that is still accepted)

- Used for the databas & for the Server Side

### Download / Clone this repository
``` 
$ git clone https://github.com/KeBinoy/FullStack_PhoneCatApp.git
```

:+1: Change your current directory to ```AngularJSPhonecat```.
```
$ cd AngularJSPhonecat
```
:+1: Create a Database ```phonecat``` in the XAMPP / WAMP /.

:+1: Import the database located at the  ```FullStack_PhoneCatApp/Database```.

:+1: Go back to the TERMINAL and Run the webserver
```
$ node mysqlPhonecat.js
```
:+1: This will create a local webserver that is listening to port 3000 on your local machine. You can now browse to the application at:
```
http://localhost:3000
```
#SCHEMA Diagram 
<img src="https://github.com/KeBinoy/FullStack_PhoneCatApp/blob/master/erd.PNG" />

#Create Module
:+1: In this module you can create new phone record and Kindly Fill in all the fields because it is required for the phone details.
<img src="https://github.com/KeBinoy/FullStack_PhoneCatApp/blob/master/create.PNG" />


#Read Module
:+1: In this module you can read or view the details of the Phone /  you can also used the search and filter function in the list view.
<img src="https://github.com/KeBinoy/FullStack_PhoneCatApp/blob/master/read.PNG" />


#Update Module
:+1: In this module you can update the Phone detail if there is changes.
<img src="https://github.com/KeBinoy/FullStack_PhoneCatApp/blob/master/update.PNG" />


#Delete Module
:+1: In this module you can delete the phone if you click the DELETE Button.
<img src="https://github.com/KeBinoy/FullStack_PhoneCatApp/blob/master/delete.PNG" />
