Alien Reporter
==============

Mobil Information Systems would like you to take a programming test.

Instructions
------------
Please create a gist with your solution and send us back the link.

Description
-----------
Alien Reporter The chaps from the backend department recently engineered a brand new API for our flagship
product _Alien Reporter_ so we would like you to help us in building an appropriate frontend. This is a very
sensitive application so we hope we can count on your discretion. Alien Reporter represents the cutting edge
technology in alien tracking. The reporter application is a way for our agents to report sightings and any
detail associated. Our agents are not very skilled at computer, so we would require you to keep an eye at
usability when designing the UI. 

The frontend will be a SPA (single page application) that will invoke the following JSON endpoint upon startup
and parse it accordingly: 
`http://www.mocky.io/v2/59f7760a2f0000ab1d55864e`

 Below is a sample output:
 ```json
 {     
	"userId": 123,
	"formId": "VC01",
	"form": [{
		"id": "F01",
		"caption": "Sighting",
		"type": "date"
	}],
	"lastChangedDate":
	"2017-10-30T17:23:43+00:00",
	"lastChangedBy": "Paddy"
}
 ```

Scope
-----
The application will display the form Id, last changed date and last changed by at the top of the page, then display a list of all the elements in the form array. The user must be able to reorder any element in the list by simple drag and drop.

Valuation
---------
You can use any javascript/CSS framework you like although the Angular 4+ framework is preferred. Priority will be given to functionality then to attractiveness and usability of UI. Any use of programming patterns, code conventions, best practices and general coding style (including appropriate commenting) will be taken into consideration and valued accordingly. Please accompany your submission with a description of the work done and reference to any framework, plugin and component used across the application. 

Points will be given to each aspect of the application up to a total of 10 points:
- Functionality: 2 points max
- Usability: 2 points max
- Coding style: 2 points max
- Appropriate use of frameworks: 2 points max
- Documentation: 2 points max

