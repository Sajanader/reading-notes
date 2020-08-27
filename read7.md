## function of javscreipt
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements)

<!DOCTYPE html> <html> <head> 
Before the closing </body> tag, you can see the link to the JavaScript file. The JavaScript file starts with a variable used to hold a new message, and is followed by a function called updateMessage(). 
<ti tle>Basic Function</title> <link rel ="stylesheet" href="css/c03.css" /> </head> <body> <hl>TravelWorthy< /hl> <div id="message">Welcome to our site!< /div> <script src="js/basic-function.js"></script> < / body> </html> 
var msg = 'Sign up to receive our newsletter for 10% off!'; function updateMessage() { var el = document.getElementByld('message'}; el .textContent = msg; } updateMessage(}; 
These statements update the message at the top of the page. The function acts like a store; it holds the statements that are contained in the curly braces until you are ready to use them. Those statements are not run until the function is called. The function is only called on the last * line of this script
delecration function to create afunction, you give it a name and then write the statments needed to achieve its task inside the curly braces.
* calling a function
having delared the function , you can then execute all of the statements between its curly braces with just one line of code. 
delacring functions that need information
sometimes a function needs specific information to perform its task. in such cases, when you declear the function you give it parameters. inside the function, the parameters act like variables.
cetting a single value out of a function 
some function return information to the code that called them. for example, when they perform a calculation, they return the result.
### EXPRESSIONS 
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions
EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE 
In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using the assignment operator (the equals sign). var color = 'beige'; 
* The value of co 1 or is now beige. 
When you first declare a variable using the var keyword, it is given a special value of undefined. This will change when you assign a value to it. Technically, undefined is a data type like a number, string, or Boolean. 
* OPERATORS 
Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 
* STRING OPERATOR 
There is just one string operator: the+ symbol. It is used to join the strings on either side of it. 


