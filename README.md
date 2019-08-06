# Long Password-Generator

# Project Description
The purpose of the project is to develop a tool that would allow me to generate a 10 character password whenever i need to create one or update my existing password to any of my accounts including github. Since i now develop tools for myself and am looking to toss new fun projects into my portfolio i want to share with you how i create this app and how it works in my world today.  

# Instructions
## HTML 
- 1.To start open a new file in vscode.
- 2.save it as passwordGenerator.html
- 3.on line one of your new html document instead of writting the entire html tree down just type ! exclamation point and hit enter it should create the entire tree for you.
- 4.inside the body of your password generator create a div and give it the id of container. 
- 5.inside the container div create 10 more divs and pass them id's of passCode1 but increment number on your id so we can identify them when we write javaScript later. Your id should look something like this passCode1,passCode2,passCode3,etc. 
- 6.dont write anything inside of the divs you just created. 
- 7.next create a div outside of the container div and give that new div the id of text-info. Inside the new div write To generate a random password click the button below
- 8.next we will create a button that we will use to generate a new password anytime you click the button. 
- 9.on the next line create another div and give that the id of messageDisplay. I'll get into more detail later on how we will have that work with the dom and js to have a message alert your new password is printed below for you to copy paste of write out completely. One thing is dont write any text in our messageDisplay id. the alert message will also be handled in js. 
- 10.finally on the next line i want you to write the final div which we will use to generate our password into text and then we should be able to copy paste to any website or password update in the future. for this final div lets give it the id of passwordDisplay. Don't write any text inside the div as javascript will handle in displaying your new password.
- 11.create a set of style tags inside the head of the html document. as an fyi the style tags in html allows you to execute css code which we will use to style the document. 

# Update 
- 1. responsive design settings added to div id int1 where when you click the minimize screen and and adjust the width to 600px the character boxes follow the design as it srinks. 
