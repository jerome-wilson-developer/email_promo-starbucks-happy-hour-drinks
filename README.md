# Starter-Kit-2018


So I built this for all the new web developers... My Goal is to save you time from the bullsh*t of spending hours looking for ways to speed up your learning. Sometimes all we want to do is just code.
(if you are coming from my  [youtube channel CodingPhase ](https://www.youtube.com/channel/UC46wWUso9H5KPQcoL9iE3Ug) I will base all my tutorials from this starter kit)

I broke it down in simple steps to get you going.

**Steps**
---------
HTML email apps use 3 table tags. the table tags are <tr>, <td>, and <table   the <tr> tags create the html structure for the application. it is used to build the containers that design the outline/form/architecture/design of the app. the containers are are designed to be either a box, a row, or a column. 
.....  the <td> tags create a container that will display the data that the endusers will see and interact with. <td> containers display html tags such as <p>, <img>, <button>, <a>, <h3>, etc.
..... the <table> tags connect the <td> containers to css so that the data can be styled, customized, and controlled. again, the <td> displays data for the enduser to interact with. therefore, the <table> tag is sandwiched between the <td> tags to connect the <td> data to css for styling. ex: <tr><td><table class="diamondSale" width="100%" align="left" cellspacing="0" cellpadding="0" border="0" style="font-family:ariel, helvetica, sans-serif; font-size:16px; color:blue; background:grey; font-weight: 500; padding:20px 20px;">  <tr><td><p>Today's Sale is 70% off All Diamonds</p></td></tr>  </table></td></tr>

This anonymous function will wrap around your app/module's code
(function() {
    'use strict'; // turn on Strict Mode

    <!-- then start your app/module's code
 }()); // end of file

Reference: MDN Strict Mode documentation
It's time to start using Javascript strict mode @NCZOnline
Important: After enabling Strict Mode, your app may no longer work - because it contains bad syntax that violates Strict Mode's requirements. This means code need to be debugged in the browser's console and fixed up for app to run.

It is a good practice to include the "use strict”; tag in your JavaScript files.

'use strict' is helpful because it forces you to write better code by preventing functions with bad syntax from executing and requiring you to declare a variable before using it. Sometimes when you implement 'use strict' you may find that your code doesn’t work. That’s because you have some sloppy coding mistakes that need to be fixed. It’s like having a very strict coding master sitting on your shoulder making sure that everything is correct before you can move on. Open Dev Tools, check the console for errors, fix them and move on with cleaner code.

Just as an FYI, when you use ES6 class syntax, that code is automatically executed in strict mode. By adding "use strict" at the top of the file you ensure that all of the rest of the code is executed in strict mode too.
Read more here: MDN > JavaScript > Classes > Strict mode https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes#Strict_mode

**Download or Pull This Repo**
	Top of this page you can see where it says clone or download

 **Install Node**
	https://nodejs.org/en/

**Download Atom**
	https://atom.io/

 **Install all the node packages** 
On the root of this project run on your terminal (if you want you can do this with yarn but thats optional)
    
    npm install
    
 **Update the node packages** 
On the root of this project run on your terminal (if you want you can do this with yarn but thats optional)
    
    npm update


**Start the server**

  npm run watch
