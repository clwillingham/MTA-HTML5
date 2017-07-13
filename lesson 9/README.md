# Lesson 9

In Lesson 9, you will be creating a javascript server using NodeJS to host your website on Cloud9 Web IDE (Integrated Development Environment)
 
### Instructions
1. Register an account on Cloud9
2. Create a new project in Cloud9 using the Empty Template
3. Within the `bash` in the bottom panel, paste the following command in: `npm install express` and hit Enter
4. Create a new file within the project called `server.js`
5. Paste the following content into `server.js`
```Javascript
var express = require('express'); //require the express package and store the module in the variable 'express'
var app = express(); //create a new server app by executing the module

/**
Create an event handler in our server, 
specifying that when it received a GET request, respond with with "hello world"
*/
app.get('/', function (req, res) {
  res.send('Hello world'); 
});

app.listen(process.env.PORT);
```

1. Visit https://c9.io and create an account
2. Navigate to https://docs.c9.io/docs/ and read 'Set Up a Database,' referring specifically to the MySQL section.
3. Follow the instructions provided carefully. If any problems arise, contact your instructor.


**Need an idea?  Pick from these prompts:**
* idea
* idea
* idea

**Criteria for the Lesson NUMBER webpage:**
* .
* .
* .

```HTML5
// Sample code should that demonstrates what should be taught in this lesson should go here
```

## Details
Details about what the code above goes here

* `Each line of code should be bulleted here`
    * A bulleted list of things about the line above should go here
    * **Really important stuff should be bold like this**
    * Keywords should be *italicized*


# Challenge Num

A challenge relating to the original sample code should go here.

```HTML5
// Sample code should that demonstrates what should be taught in this lesson should go here
```

* CRITERIA
    * item
    * item
    * item
