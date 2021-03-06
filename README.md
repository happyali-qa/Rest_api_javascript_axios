## REST API JavaScript Test Automation Framework
======================================================================

## Overview

	* This is simple project to showcase Api Test Automation Framework in JavaScript using mocha.
	* Skills: Api Test Automation, Modular Design
	* Languages: JavaScript/ Node.JS
	* SCM: Git
	* Build/Dependency Management: npm, Axios
	* API Testing Frameworks: Mocha, REST Api, Data-Driven (Json)
	* Assertion Lib: Chai, Expect, Should

## Setup

	* Download [javascript-api-mocha](https://github.com/happyali/techTask.git) Project from GitHub
	* Install latest [Node.JS](https://nodejs.org/en/download/)
	* Install latest [Visual Studio Code](https://code.visualstudio.com/download)


	* Open another Terminal window and Navigate to Test_Framework Directory
	* Run `$ npm install`
	* Run Tests `$ npm test`

## Bug Reports
	* Issues identified while scripting or run are reported in "./BugsReport" folder in project

## Sample API Test Scenarios
    
	    1. Call End point to get Weather details with respect to LOCATION (Lat, Log) 
	    2. Call End point to get Weather details with respect to POSTCODE
 
## Pipeline for CI is implemented using CircleCI
======================================================================
	
	* You can find the current running pipeline at https://app.circleci.com/pipelines/github/happyali-agl/Rest_api_javascript_axios
	* Currently it is throwing error as:
		" Error: Cannot find module '../resource/datafile/endPoints.json'"

## Test Run Report
======================================================================
	
	* The automation run report created using Mochawesome Reporting can be found at : "Rest_api_javascript_axios\Test-Framework\mochawesome-report\mochawesome.html"
   
