Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

QUESTIONS:

2. We get the value 0.
3. If too much money is inserted, the machine will print a ticket but the balance
value will become 0 regardless of how much more money than the cost you put in.
If not enough money was put in, the machine will still print a ticket.
5. It does look different. The price displayed at the bottom of the ticket has changed.
6. public class Student or public class LabClass.
7. If it is written as class public TicketMachine, then the class will return an error.
The error message i got was "<identifier> expected". Although curretly I don't really understand
what it means, hopefully in the future I will.
10.
Fields:
Price - private int price
Balance - private int balance
Total - private int total
Constructor: TicketMachine
Methods:
getPrice
getBalance
insertMoney
printTicket
11. Constructors do not have any return type and a constructor's name must be identical to the class name.
12. 
private int count - int
private Student representative - Student
private Server host - Server
13.
private boolean alive - alive
private Person tutor - tutor
private Game game - game
15. Yes, the order it appears in is important.
16. Again. it is important, because if not put, any other code put in after that line will not be considered
as the same line.
18. It belongs to the class Student.
19. It has two: title of type string and price of type double.
20. Yes, the parameters need to be stored somewhere persistent.

21.
 
public Pet(String petsName)
{
    this.name = name;
}

22.

public Date(String newDate)
{
    date = newDate;
}

23.
Headers: the name of methods is different (getBalance, getPrice).
Bodies: the field that is being returned is different (balance, price).
24. "How much money is in the ticket machine?"
25. No it doesn't, because you are only changing the name of the method, not what to return.
27. I get the error "not a statement.
28. The method type is different. While the getPrice method's type is a getter,
the printTicket method's type is a printer. Also getPrice has a return statement while printTicket does not.
29. No they do not. That is because they don't need to return any value.

31.

/**
* Increase score by the given number of points.
*/
public void increaseScore(int points)
{
    score = score + points;
}

32. Yes it is a mutator. It is changing the value of the field.

33.

/**
* Reduce price by the given amount.
*/
public void discount(int amount)
{
    price -= amount;
}

34.

public void setAge (int currentAge)
{
    age = currentAge;
}

35.

private boolean alive;

public void setStatus (boolean vitalStatus)
{
    alive = vitalStatus;
}

36. Even after inputing a price, the getPrice method still returns a value of 0.
37. My cat has green eyes.
39. When you call the method, it will print the word price and not the value of the field price.
40. It will print out: # price cents.




