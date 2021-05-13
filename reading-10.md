# I will take notes on my reading related to Bugfixing/Debugging

### Debugging

If you anticipate that some code you write will  cause an error you can create an exception to the error to tell the code to ignore the error. 

Learning to read the type of errors is helpful in determining where the code is wrong.

Some error types include: Syntax, Reference, Eval, URI, Type, Range, Error, NaN.

* Syntax - Error in coding by missing something like closing a bracket.
* Reference - not declaring the variable correctly.
* Eval - rare probably wont show up
* URI - using special characters such as & in code but forgetting to escape with a backslash.
* Type - Incorrect case for document object or write method. 
* Range - If a value exceeds the length of an array or given range.
* Error - genereric error prototype for other errors.
* NaN - not an answer like when multiplying a number by a string.

You can start fixing errors by debugging through the website's console. 
Breakpoints are important to allow the code to stop and be read by the programmer at certain points.



#### Credits: The Reading notes are derived from Javascript&Jquery by Jon DUCKETT
[<-Back](README.md)





