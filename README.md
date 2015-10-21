## Deprecated-method-search

# Goal

Project is aimed on getting all deprecated methods from specific Mozilla MDN web-site in a JSON format.
This project is taking info from left side bar of the web page.

![alt text](https://github.com/ToPeter/deprecated-method-search/sidebar.png "Mozzila MDN side bar") 

## Before you run 

You need folowing npm packages: 

	$ npm install fs
	$ npm install request
	$ npm install cheerio

## How to run 

	$ node deprecated.js

If you want to change web-site from where you are getting the result then change url attribute in code.


## TODO

Find the web-site where are listed all Javascript deprecated methods.

Closest to it: 

	https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features

	https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index


