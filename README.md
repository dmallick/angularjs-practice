# angularjs-practice

How tp Set Up
================================================================
Make folder: C:\xampp\htdocs\angular-js
cd C:\xampp\htdocs\angular-js
set PATH=%PATH%;C:\Users\dmalli\AppData\Roaming\npm;
install bower: npm install -g bower-installer / npm install -g bower

To install angular: 
D:\xampp\htdocs\angular-js>
	bower install angular
	bower install angular-route
	bower install bootstrap


D:\xampp\htdocs\angular-js>	
mkdir js
mkdir css
mkdir images
set path =%path%;C:\Users\dmalli\AppData\Roaming\npm;
D:\xampp\htdocs\angular-js> npm install http-server -g

Copy the following JavaScript file D:/xampp/htdocs/angular-js/bower_components/angular/angular.min.js into the directory /js directory
Copy the following JavaScript file D:/xampp/htdocs/angular-js/bower_components/angular-route/angular-route.min.js into the directory /js directory


D:\xampp\htdocs\angular-js>http-server -o. -o

Main Components:
===============================================
Creating a Module
Controller given in controller-example.html
encapsulating module and controller in module-directive-injs-example.html

AngularJS Filters
AngularJS provides filters to transform data:

currency Format a number to a currency format.
date Format a date to a specified format.
filter Select a subset of items from an array. - Filter-Array-Basedon-Userinput.html
json Format an object to a JSON string.
limitTo Limits an array/string, into a specified number of elements/characters.
lowercase Format a string to lower case.
number Format a number to a string.
orderBy Orders an array by an expression. - sort-array.html
uppercase Format a string to upper case.



AngularJS Services
==============================
In AngularJS, a service is a function, or object, that is available for, and limited to, your AngularJS application.

$location service has methods which return information about the location of the current web page
The $http Service The service makes a request to the server, and lets your application handle the response. - http-service-example.html

