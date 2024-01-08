# Restaurant-Ordering-System

This is a system in which several devices set up in a restaurant will allow customers to order their food using the installed program. This automates the ordering process and allows service without counter attendants. The customers are dealt with on a first come first served basis.
Features
This system will consist of the following features:
(1)	 Data Structures:
Different data structures will be used to make our program so that it becomes more time and space efficient. The following will be included:
o	Stack:
This will be implemented to confirm each item of the order by simply using the pop() function and asking the customer if they want that specific item or they want to remove it from the cart. And after everything is popped, the information of the popped items will be sent to the kitchen for its preparation and a bill will be generated.
o	Queue:
This data structure will be used to process the customers’ orders using the FIFO (first in first out) method. As the restaurant has more than one machine, the orders will be processed through a queue, one order at a time for the customer who is able to finalize their cart first.
o	Trees:
This data structure will be used to store and manage the information of the different cuisines we provide in our restaurant. The roots will contain the names of the cuisines and their children nodes will have information about the dishes and their prices.




o	Circular Doubly Linked List:
The roots of several trees (the cuisines) will be linked together by using a Circular Doubly Linked List. The customer will be able to move from one cuisine to the next until they reach their desired cuisine.

(2)	 Object Oriented Programming:
OOP will be used to manage our code easily, for structure and to access any module whenever required. We will make classes, objects etc to make our code look organised and presentable.
(3)	 Exception Handling:
Exceptional handling will be used to handle errors. The following will be used: while loops and flags.
(4)	 Pandas and File Handling:
Since we will be making use of CSV files, the pandas library and file handling will be used for efficient access. These CSV files will maintain a record of the items of the different cuisines. To print the bill in an appropriate format we will make use of a .txt file.
(5)	Pysimplegui:
Pysimplegui will serve as the front end of this program. It’s easy to use with simple customizable features of a graphical user interface for Python. It is based solely on Tkinter. There will be different pages that will pop up accordingly. For example, the page for account registration, the menu page, etc.
Methodology
When the customer runs the program, he/she is presented with a cuisine selection interface where he/she will be able to select any cuisine he/she wants by using the next and previous options. After he/she finalizes any cuisine he/she can choose it and move on to the next interface in which he/she will be given a choice whether he/she wants to order the desired thing by typing the Unique Product ID or wants to filter the meals according to their category i.e., Spicy, Sweet, Sour etc. After he/she is done with the selection of the category he/she will be presented the items with the similar category and the items can be selected by using the Unique Product ID. After he/she is successful in adding the required item in the cart. The ordering process is repeated until the customer manually returns from the ordering method interface to the cuisine selection interface. In the cuisine selection interface, he can choose an option named Confirm Order in which the customer is given the choice if he/she wants to keep an item in the cart or discard an item. After the confirmation process is done an amount is generated and the customer is asked if he wants to login/register/skip the account registration process. The account holders will get an additional 10% discount from the total bill and the total amount to be paid is generated. The order details of the customers are saved in a queue for record purpose.
