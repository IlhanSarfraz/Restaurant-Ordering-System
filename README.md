# Restaurant Ordering System

This project involves the development of a restaurant ordering system where customers can place their orders using installed programs on various devices within the restaurant. This system aims to automate the ordering process, eliminating the need for counter attendants and providing a first-come-first-served service.

## Features

### 1. Data Structures

Various data structures are implemented to enhance the efficiency of the program:

- **Stack**: Used to confirm each item in the order, allowing customers to review and modify their choices before sending the information to the kitchen for preparation.

- **Queue**: Utilized for processing customer orders in a first-in-first-out (FIFO) manner, especially beneficial in a multi-machine restaurant setup.

- **Trees**: Implemented to store information about different cuisines, with roots representing cuisine names and children nodes containing details about dishes and prices.

- **Circular Doubly Linked List**: Connects the roots of multiple trees, enabling customers to navigate between cuisines seamlessly.

### 2. Object-Oriented Programming (OOP)

OOP principles are applied to enhance code organization and maintainability. Classes and objects are used to structure the code effectively.

### 3. Exception Handling

Exception handling techniques, such as while loops and flags, are employed to manage errors and ensure a smooth user experience.

### 4. Pandas and File Handling

The program makes use of CSV files, utilizing the pandas library and file handling for efficient data access. CSV files maintain records of items in different cuisines, and a .txt file is used for generating bills in an appropriate format.

### 5. Pysimplegui

Pysimplegui serves as the front end, providing an easy-to-use graphical user interface for the program. Different pages, including account registration and the menu, are designed for user interaction.

## Methodology

1. **Cuisine Selection Interface**: Customers are presented with a cuisine selection interface where they can navigate through cuisines using next and previous options.

2. **Ordering Interface**: After selecting a cuisine, customers can choose items by entering the Unique Product ID or filtering meals based on categories like Spicy, Sweet, Sour, etc.

3. **Cart Management**: Customers can add items to their cart, and the ordering process is repeated until the customer manually returns to the cuisine selection interface.

4. **Confirmation and Account Handling**: Customers can confirm their orders, review and discard items from the cart. Account registration/login options are provided, with registered users receiving a 10% discount.

5. **Order Processing**: Order details are saved in a queue for record-keeping purposes, and the total amount to be paid is generated.
