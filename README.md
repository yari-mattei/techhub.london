TechHub.London
==============

This is the GitHub page for Techhub.London, TechHub’s guide to the best of the local area. All of the information on the website is Open Source, and if you have better suggestions, you are welcome to edit the code and add them! 

You can find the source in the [master](https://github.com/techhubdotcom/techhub.london/tree/master) branch, while the live pages are in the [gh-pages](https://github.com/techhubdotcom/techhub.london/tree/gh-pages) branch.

## Getting started

There are two ways to edit the website:

Noticed a typo? Have a great place to add to one of the lists? If all you want to do is to edit some of the text, follow the ‘simple edits’ instructions below. If you would like to make changes to the layout, or want to see how that pages will look when your changes have been made, you can see the ‘advanced edits’ instructions.

We ask that all additions fit these criteria:

- It will be a helpful addition to other people using the website
- It only contains links to relevant websites or relevant text
- It doesn’t cause the website to break or contain malicious code

Any edits that do not fit the criteria sadly will not be added to the website :(

## Simple edits
For simple edits, all you need to do is fork the code, edit the HTML pages in the `app` folder and send us a pull request. 

## Advanced edits
You need [Node.js](http://nodejs.org/) installed to run [Grunt](http://gruntjs.com/).  
I really suggest you to install Node.js with a packet manager, instructions can be found [here](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager).  

- Install Node.js and verify that everything is alright with `node -v`
- Install Grunt-cli with `npm install -g grunt-cli` 
- Fork the project and clone it on your machine
- Install npm modules dependencies with `npm install`
- Install bower dependencies with `bower install`

## Developement
Run `grunt serve` and start editing the pages that you find in `app/` directory.  
It will fire a browser with livereloading feature enabled.  
Happy coding!

## Build
Run `grunt build` to build the project into `dist/`  
Pull request when you are done ;)

## Made with
- Bootstrap3
- jQuery
- FontAwesome
- Yeoman
- Node.js
- Grunt
- Bower

## Version

0.1 Hello world :)

TechHub.London is licensed under the terms of the MIT Licence - see the License.txt file in the root directory for more details. 

