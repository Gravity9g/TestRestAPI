# Test  API With ReactJS 

* I came up with this small module which will help you to test api in ReactJS

But first you have to install nodejs in your Windows machine thats the minimal reqirement this module needs

# How To Install And Setup node environment 
In zip file there is another readme file go through it.
it merely takes few minutes to install

# How to prepare Request And Call API
Ok as per my observation we have mainly to types of request.

 * Without File or Media attachments.
 * With Media Files.
  
first type of request you can easily test on DB your own 
problem is with 2nd type of request i.e with media file
  
  so was i created simple web page where you can upload file and call api

# worst part :-(
  # Preparing request

Ok this you have to do it your self because each api call have different parameters and type,name also (it would be great if we follow same naming convention in api param)
so in Input.js file  i commented code as simple as possible so you can under stand

So basically there are to main Function calls 

* testAPI()
* testFileAPI()

testAPI() for without media file API
testFileAPI() for with media file API

In both of them you have to prepare request your own. Have a look in code i created dummy request there

# Input.js  >> TestAPI/Component/Container/Input.js
this is the main file where you can find all code and api calls 
(actully i wanted to create module as per our standerd but i don't have that much of time so was all mess in one file )

ok thats it !!
thats all i wanted to tell you !!! 

ping me if messed with any fail or erroe



