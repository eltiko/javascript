# programming with javascript
JavaScript is a programming language created in 1995.

JavaScript allows us to create **interactive and "live"** pages using scripts.

A script is a sequence of instructions that will be interpreted by a program; a web browser.

## Where to write our JavaScript code?
the JavaScript code can be placed in three different places:

In the head element of an HTML page;
In the body element of an HTML page;
In a file with the extension ".js" separated.
however it is best to write it in a separate file.
## The syntax of JavaScript
with javascript the syntax is to give commands to execute using lines of code with variables
A **JavaScript variable** is a container for temporarily storing information>
example; 
*var texte = "Bonjour", x = 4, b = true, n = null, u, nn = NaN;
        
        alert("Variable texte : " + typeof(texte) +
              "\nVariable x : " + typeof(x) +
              "\nVariable b : " + typeof(b) +
              "\nVariable n : " + typeof(n) +
              "\nVariable u : " + typeof(u) +
              "\nVariable nn : " + typeof(nn));* 
## OPERATIONS ON VARIABLES
You can perform operations between variables.

For variables storing values of type Number, one will thus be able to carry out the same operations as with numbers in mathematics.

Thus, we will be able to add two variables between them, subtract them from one another, multiply them between them ...
You can perform operations between variables.
*var x = 5, y = 10, z = -2;
        
        //Les priorités de calcul sont les mêmes qu'en mathématiques !
        var priorite = x + y / ( 4 + z ) % 3;
        
        alert(priorite);*
