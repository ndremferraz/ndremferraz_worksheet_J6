# Worksheet J6
## Question 1.
The program output has changed for everytime that I run it. Sometimes the afternoon thread starts before the morning thread, the number os greeting of a thread before the other is never the same. 
//add image later

## Question 2.
I ran the program at least 5 times and for all these executions the similar was the same, with the afternoon thread being run first and the greetings interleaving one after another perfectly. The only difference is that sometimes one thread would finish before the other. 

## Question 3. 
Each thread is running its individual program in parallel with the other threads. When the two other threads start the main method keeps running simultaneously, and the program waits for all threads to be done to finish its execution. 

## Question 4.
Attempting to join the threads after 5 seconds makes sure that thread 1 will run for 5 seconds before the main thread and thread 2 start their executions. 

## Question 5. 
join() will wait for the thread that it is called upon to be done before executing the thread it is on. join(int delay) will wait for delay milliseconds before executing the thread it is on. 

# Question 6. 
isAlive() checks wether on not a thread is still running, and join() will wait for the thread to finish running. 

# Question 7. 
The program output shows that the Cheetah, will always finish first, then the Hare, and, finally, the tortoise. Even though the starting order may change. That happens because in the run function, each thread will sleep for a time inversely proportional to their speed. 



