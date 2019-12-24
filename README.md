# UC-UI
## Unified Calendar - User Interface
![Logo](https://omextemplates.content.office.net/support/templates/en-us/lt16410086.png)

## Objective

Building a web application with its own database, that imports calendar data from other systems in other networks, the system shall allow logged in users to view all calendar events from different systems in layered view. Users can also add additional events directly through the web interface. Managers shall be able to view the calendars of their teams.

## Features

  * Manager able to view all calendar events of each team/employee
  * Employee able to view/ add events directly – on date/time range in UI
  * Multiple views of calendar – day | week | month | year
  * Display calendar events that are pending/confirmed differently
  * Web based responsive interface


## Data Sources
1. Microsoft exchange server
2. Gitlab

## Main Parts :

* Middleware-server:

       Runtime            	    : Node.js
       Framework       	    : Express.js	
       Database          	    : Mongo 
       Unit-testing               : Jest
       Package manager            : NPM
      
* Web-UI:

       Web tech      : HTML, CSS, JavaScript
       CSS		       	: bootstrap, font-awesome
       UI lib        	: React.js
       State management    : Redux.js
       Build tools    	: NPM 
       Unit-testing   	: Jest
       End-to-end    		: selenium, cucumber
       
* Authentication/Authorization server.


