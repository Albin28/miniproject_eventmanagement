# miniproject_eventmanagement
project for an event management program using circular queue
Event Management System in C

This C program implements a simple event management system using a dynamically resizing queue. Users can add, remove, and view events in the queue. Each event includes details such as name, date, description, and phone number.

Features:

1. Add Event: Allows users to input event details, which are then added to the queue.


2. Remove Event: Dequeues the event at the front of the queue.


3. Display Events: Lists all events currently in the queue.


4. Dynamic Resizing: Automatically resizes the queue capacity when it’s full, doubling its size to accommodate more events.



Code Breakdown:

Structures:

Event: Holds event details like name, description, phone, and date.

EventQueue: Manages the queue of events with properties like front, rear, size, and capacity.


Functions:

initialQueue: Initializes the queue with a given capacity.

isFull and isEmpty: Checks if the queue is full or empty.

resizeQueue: Doubles the queue's capacity dynamically.

enqueue: Adds a new event to the queue.

dequeue: Removes an event from the front.

displayQueue: Displays all events in the queue.

getEventDetails: Prompts the user for event details.



How to Use:

Run the program, then select options to add, remove, or display events in the queue. The program will resize the queue as needed and ensure that events are managed in a FIFO order.
