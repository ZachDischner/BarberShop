Zach Dischner
=================================================

**Jan 13 2017**

**Coding Challenge - Barber Shop Simulation**

**Time limit: 2 hours hard cutoff** (holy cow, probably coolest and most intense challenge I've had to date)

## Execute
Just run from the command line:

```
python BarberShop.py
```

## Prompt 
==Goal==
Your task is to simulate a massage parlour.

==Rules==
The Barber Parlor is open for 8 hours, from 9am to 5pm. You don't want your program to take that long to run, so you'll need to somehow simulate real time.

When the parlour opens, there are 4 Barbers who start their shift:
Alto, Basil, Camphor, and Diogenes.

On average, a new customer enters once every ten minutes. Their arrivals are random. Customers are named successively starting at Customer-1. The parlour can only hold 15 total customers; if a customer arrives when the parlour is full, they leave impatiently.

Otherwise, the client waits for a Barber. A Barber can only massage one person's back at a time, and takes between 20 and 40 minutes to do so. After a Barber is done with a customer, the customer leaves satisfied.

A customer will wait up to 30 minutes for a free Barber; if time's up and none can be found, the customer leaves unfulfilled.

Barbers work 4 hour shifts, so the first shift of Barbers is allowed to go home at 1pm. They end their shift as soon as they can, unless they busy with a client. In that case, they wait until they finish that client, and then end their shift.

At 1pm, the second shift of Barbers starts: Eros, Fatoush, Glorio, and Heber. They also work a 4 hour shift, and can go home after 5pm. Like the morning shift, if they're busy with a customer, they need to finish up before leaving.

A customer who enters after 5pm is turned away, and leaves cursing himself.

When all the Barbers and customers have gone home, the parlour closes. If there are any customers left waiting for a Barber, they are kicked out, and leave furious.

==Output==
Your program should print the below events in chronological order.  [Time] is Barber parlour-time in the format HH:MM, not real time.

[Time] Barber Parlor [opened/closed]
[Time] [Barber] [started/ended] shift
[Time] [Customer] entered
[Time] [Customer] left [impatiently/satisfied/unfulfilled/cursing himself/furious]
[Time] [Barber] [started/ended] massaging [Customer]'s back

==Guidelines==
Use your choice of language. Use only standard libraries. Use whatever resources you'd like, apart from asking about the question itself online.
