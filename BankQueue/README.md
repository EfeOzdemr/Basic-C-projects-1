

you are going to write a queue simulation for bank costumers. We assume that, our queue length
is constant (10 as maximum length). We use a constant integer array to simulate our queue structure.


A queue is one of the simple data structure which works in FIFO (First In First Out) logic. The information always
read(delete) from the beginning of the queue and written(add) from the end of the queue.


In our simulation we use a constant length integer array to store data in queue logic. To simulate the queue an
array to show the start and finish position of the queue two pointers is going to be used in the simulation. This
pointers (or we can call index positions) are take the same position on the array in two situations; when the queue
is empty and when the queue is full. The written simulation must warn the user when the queue is empty and the
user is trying to delete a costumer or when the queue is full and the user is trying to add a new costumer.


The simulation consists of three functions:
   1. Read an integer number (something not important for simulation. Think like costumer’s id)
   2. Read the next costumer in the queue, remove it from the queue and print the costumer id to the screen.
   3. Write the costumers id numbers inside the queue from the beginning to the end.


From a simple input screen the user will chose one of these functions in an infinity loop till he wants to exit from
the program.


The sample output screens of the program shall be something like below.



**SAMPLE OUTPUTS**<br/>
Main Menu:  
1. Enter New Costumer into queue <br/>
2. Read the next Costumer from queue <br/>
3. Write out the Costumers in queue <br/>
4. Exit Simulation.
