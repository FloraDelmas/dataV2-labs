![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations
In this lab we are going to put into practice what we learned about the foundations of statistics. You won't need to use Python, just your brain and a little bit of *Markdown*. 

## Your task
Today you'll need to complete the challenges described below.

## Deliverables
You need to submit a markdown file with the solution to the following challenges. You can create a new *.md* file or directly edit the *README.md* to include your solutions.

## Challenges
### Challenge 1
One player rolls two dices. Describe the measurable space and the random variable for:
* A. The values that the player obtains.
1    1
1    2
1    3
1    4
1    5
1    6
2    1
2    2
2    3
2    4
2    5
2    6
3    1
3    2
3    3
3    4
3    5
3    6
4    1
4    2
4    3
4    4
4    5
4    6
5    1
5    2
5    3
5    4
5    5
5    6
6    1
6    2
6    3
6    4
6    5
6    6
= 36

* B. The sum of the values obtained.
=11

* C. The maximum value obtained after rolling both dices.
6

Describe the following events:
* Case A: Both values are greater than 5.
6    6
=1/36
=11,11%

* Case B: The sum of values is even.
50%

* Case C: The maximum is the value of both rolls.
6*(1/6)*(1*6)=1/6

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.
Measurable spaces is 3; pick 2 or 1 on 0.
(12/52)*(11/51)=4,8%
((40/52)*(12/51))*2=36,19%
(40/52)*(39/51)=58%


* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
25
30
=Measurable space is 19

* C. The number of hearts or spades he picks.
13
25%

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
(12/52)*(11/51)=4,8%

* Case B: The sum of card values is 17.
8+9
10+7
J+7
Q+7
K+7
A+2
=6times * (4*4) colors
=96/(52*51)
=3,6%

* Case C: The value of both cards is less than 8.
(6*4)
=(24/52)*(23/51)
= 20,81%

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
6

* B. The greatest score.

* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 

Describe the following events:
* Case A: The score of player A is 2.
* Case B: The greatest score is lower or equal than 2.
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  * Player A loses more than 2 coins.
  * Player A neither wins nor loses coins.

## Bonus challenges
### Bonus Challenge 1
Three players take balls from a box. Inside that box there are red, blue, green and black balls. The players can take three balls at mosts with the following rules:

* If the ball is blue, they can take another ball.
* If the ball is green, they get one point and they can take another ball.
* If the ball is red, they can’t take another ball.
* If the ball is black, they lose one point and they can’t take another ball.

Describe the measurable space and the random variable for:
* A. Player A wins. Do not consider ties as a win.
* B. Player A and B get the same points.
* C. All players get 0 points.

### Bonus Challenge 2
Consider the situation of bonus challenge 1 but now with four players. Does anything change in your solutions? What are the changes in each case?

### Bonus Challenge 3
One player takes three balls from a box. Inside the box there are 5 balls: two of them are black and the other three are white. 

Describe the measurable space and the random variable for:
* A. The number of white balls if every time we take a ball we keep it.
* B. The number of white balls if every time we take a ball we put it back again into the box.
* C. The number of black balls if every time we take a ball we keep it.
* D. The number of black balls if every time we take a ball we put it back into the box.
