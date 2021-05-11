# I will take notes on my reading related to Tables, Functions, Methods, and Objects

### Tables
A table is a way to show information in a grid format. It is one of the most common ways to display data.
A table is created by using the ```<table>``` element. Inside each table there is a number of ```<tr>```These create the rows of the table. Inside each row is ```<td>``` This creates the cells and stores the actual data in the row. ```<th>``` is and element used much like the ```<td>``` element that is used as a header. You should use either of those tags on a cell even if it is empty.

You can use the colspan attribute on a ```<th>``` or ```<td>``` element to designate how many columns the data should run across.
Ex. ```<td colspan="3">Tacos</td>``` the same format is used for rowspan. 

```<thead> <tbody> <tfood>``` are elements that designate the three sections of a table. 

### Objects
Creating objects is easiest when making a constructor function. They are formatted by 
```function Hotel(name,rooms,booked){
    this.name = name;
    this.rooms = rooms;
    this.booked = booked;
}
```
To create a new object just make a new variable and name it then assign it to a new hotel object in this instance then pass in the required parameters.

#### Credits: The Reading notes are derived from Javascript&Jquery by Jon DUCKETT
[<-Back](README.md)
