## Digital Clock 

Sooo this digital clock had like 3 main parts
 - Initializing the reference point
 - The time pointer
 - The flag of it still running

We(I and yt video) used a variable type called time_t, that is basically the referrence point that we do all our calculations from its 1970 January 01,
the calculation on getting current time is taking the amount of seconds its been since that referrence point and doing calculations to get the year, month and day of
now. Its really cool to think off, I heard that a humans life is around 2.5 billion seconds and when you do the calculation till right now its been around 1.7 billion seconds
its crazy right? Almost a whole human life in such short time. 

Either way back to the code then a struct pointer is used to represent the current moment, the reason its a struct is because there a number of ways to represent the current moment
in time, it could be seconds, minutes, hours, days, months, years, etc. So we need a struct to access each of those representations. The pointer is because that constantly changing
seconds number is not calculated in the file itself but rather on my pc. Almost like im borrowing that changing number from my machine to use in this digital clock.

Set running to true :)

Now while running is true we need to do the following:
- Get that rapidly changing number
- Localize it to work in the struct pointer
- Print the current time and change it every second

First part is achieved by just saying the time header and using the address of the time_t variable, next we use a function called localtime to the same memory address so that it fills
the struct with whats needed and finally we do some weird formatting trick where in the printf statement we have in quotes the amount of digits we want and their formats, then 
next to that we specify which digit is placed where respectively. Finally we put a sleep function so that it updates every second and looks like a real clock.


I give this code:
- Cool scale: 8/10
- Simple Code: 9/10
- Usability: 8.5/10

Great Code and Great Logic, I can add this to my belt of development now :)

Ricode Out!



