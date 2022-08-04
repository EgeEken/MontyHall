# Monty Hall
 A simulated demonstration of the famous statistical puzzle, the Monty Hall problem.

![image](https://user-images.githubusercontent.com/96302110/165195538-c3ad3c02-0a45-48eb-b94e-7eb07521b74b.png)

In this game show, the host offers you a choice between 3 doors, behind one is a car, behind the others are two goats. After you make your first choice, the host opens another door, revealing a goat, leaving two unopened doors, which have inevitably one goat and one car. The host asks you if you want to switch your choice to the other door or not.

It seems like the probability of you getting the car in either case should be the same since it's a choice between two doors, one of which has a car behind and the other a goat. 50/50, right? Wrong. Due to the added information after the initial choice, the probability of the result changes depending on whether or not you switch your door. Making the actual chances 2/3 and 1/3 if you switch and don't switch respectively.

What is more interesting to me is that when you increase the door count, the difference grows, the chances stay as (door count) - 1/(door count) and 1/(door count). Meaning that if you were given a choice between 100 doors, you chose one, and the host revealed 98 doors, despite still choosing between two doors, one with a car, one with a goat, your chances of winning are 99% and 1% based on whether or not you choose to switch

![image](https://user-images.githubusercontent.com/96302110/165194877-3090f710-3c5d-49b0-846d-86210266eeda.png)

![image](https://user-images.githubusercontent.com/96302110/165194957-282b3e03-b276-45b0-96e3-b0dea0735fe0.png)
