# DSA-Project
Data Structure and Algorithms was one of my core subjects of 3rd semester. We studied in detail about lists, linked lists, doubly linked lists queues, stacks, sorting etc. in Python Language. We applied our knowledge from this course to our project. 

## Blood Donation App
The essential link between blood and physical health is blood. We created an app to serve that objective and show compassion to those in need of blood. Our network of kind contributors, volunteers, and staff members is dedicated to avoiding and alleviating suffering both domestically and internationally.

## Methodology
We applied the knowledge we gained in Data Structure and Algorithm course and did some self-study in the compilation of our code. The main two modules of our application are:

- Donor
- Receiver
These both modules are buttons. The user presses either and then another tab opens.

### Donor:

If the donor button is pressed, then the user is asked for following information to donate blood:

- Name
- Phone Number
- Blood Type
- City

When the receiver button is touched, the user receives a serial number and a list of donors, with a serial number assigned to each donor. The user is then prompted to input their serial number before being taken to the next tab and questioned about whether or not they have got their blood? The donor is added to the inactive list and removed from the active list after selecting "yes" on the pop-up. File handling is also a part of all of this. For each active list and inactive list, we keep two files that are updated in accordance with the tasks completed. The user is subsequently returned to the receiver tab where they can reapply to receive blood if the "no" button is hit.

## Specifications
The specifications of our project are as follows:

- We used Double Linked List as our data structure to minimize the time complexity.
- We used global variables and objects for easy access and to avoid the difficulty of defining the same variable again and again.
- We used Kivy as an external library for GUI.
- We used file handling to handle the data of the donors.

## How to run the App?
Simply import kivy library to your python compiler and run the attached program.
