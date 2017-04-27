# Sample Deployment Instructions / Readme.md

* **Note**: This is pseudo sample file attached with the hackathon or task-based submission to deliver clearn understanding.

# Problem Statement

Build a pseudo web application to list real-estate properties and browse them.


# Technology Stack

This application is built on LAMP stack.

* PHP 5.5.X
* MySQL 5.6.X
* Yii 2.0.6

# How to Run

You must have installed all software mentioned above
 
To run:

* Goto `/src` directory
* Check if all required PHP modules are installed
		 
		php requirements.php
	If you found any error, please install that PHP extension
	
* Run composer create-project
* To load sample data 

	    ./yii migrate
    
* Start PHP's buil-in server

		php -S localhost:8080 -t web/
    
* Open [http://localhost:8080](http://localhost:8080) in your browser

## Demo*
Live demo is also hosted at  [http://propertyguru.demo.abhi9.in](http://abhi9.in)

# Implemented Feature

* Property search and listing
* Filter by various attributes
* Sorting
* Property Detail
* Location on Map
* Like property using local storage
* Intitutative design


### Todos / future aspects

 - Write more features
 - Add Chrome Extension
 - Code refactoring
 - Support for WebSockets, WebSQL and CDN


### Architecture

[![N|Solid](http://i.imgur.com/Dc5KSJ5.png)](https://aws.amazon.com/getting-started/projects/launch-lamp-web-app/)


### Sample Wireframe / Screenshot
![Sample Wireframe](http://i.imgur.com/mp5naGe.png "Sample Wireframe / Mockup")

### Portfolio / On the web.

Feel free to buzz me at `mayur {at}  pipaliya [.] c o m` in case of any query or confusion.

- [Stackoverflow]
- [Linkedin]
- [Github]
- [etc]

License
----

MIT


**Help spread the free software. Hell yeah! ❤️**



   [Stackoverflow]: <https://stackoverflow.com/users/866571/mayura>
   [Github]: <https://github.com/mayurah>
   [Linkedin]: <https://www.linkedin.com/in/mayurpipaliya>
   [etc]: <https://mayur.pipaliya.com/>
   
