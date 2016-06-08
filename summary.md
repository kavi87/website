1. Introduction
	- General ideas about testing
	- What is testing, why

2. Tools
	- NodeJS
	- Jasmine (other frameworks, like mocha)
	- Karma
	- PhantomJS

3. Installation
	- How to install tools

4. Configuration
	- karma.conf 
	- test.main in general and in w20
	- examples
	- window.w20

5. Writing tests
	- General test structure
		- define, beforeEach ...
		- describe
		- it
		- spies
		- expect

	- Angular specific
		- Show examples each time

		- how to mock modules (angular.mock.module)
		- underscore stripping (_$rootScope_)
		- How to mock dependencies
		- $httpBackend service
		- handling asynchronous test
		- $provide

6. Some examples
	
	- clock.js example with comments: show the actual code and what it does and then show how to test it
	- example with fake server data
	- a full example: repository with all the config and some tests