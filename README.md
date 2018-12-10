# milestone1-135
9/9/2018:
- Storyboard was designed to show the end product of the vending machine. Both the customer input and output as well as the service worker's input and output were shown. 
- UML diagrams were created for both the item class and dispenser class.

9/23/18:
- Inheritance hierarchy was created to show the relationships between each class
- Each class was implemented, with the product class and snack class being abstract.

10/7/2018:
- Comparable interface was implemented into Product class.
- Updated UML
- Driver class was created. This tests the compareTo() method.

10/24/2018:
- User interface was created 
- Transaction class was created

11/5/2018:
- InventoryManager class was created
- Animation created and implemented into vending machine (still need to improve animation of item falling into basket)

12/1/2018:
- Global Inventory Manager was created and implemented in the Vending Machine class (Machine.java)
- CSV file contains information about items in the main vending machine and second vending machine
- Name and quantity properly uses recursive sorting method to sort items
- Item search properly uses recursive search method to search for item within both vending machines
- Restock class was created and implemented in the Vending Machine class
- Restock generates a purchase order for items with quantity of 3 or less. Quantity to order is 10 items
   and total price is displayed.
- Still working on re-designing vending machine in order to function correctly when being used.

12/8/2018:
-  CSV file contains list of customers with purchase
- ProcessCustomerQueue class was created and implemented in Vending Machine (Machine.java)
- Queue methods first(), length(), in(), out(), isEmpty() are used within the class
- Transaction is processed, if item is not available, then it is replaced with a random item
- Removes customer from queue once transaction is processed
- CustomerDisplay is created and extends Application
- GUI displays each customer's interaction with the vending machine (name, item purchased, price)
- Vending Machine is still being worked on 

