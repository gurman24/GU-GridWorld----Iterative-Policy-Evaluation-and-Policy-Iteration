by Gregory Urman

www.linkedin.com/in/gregoryurman   
<br/>

# GU-GridWorld ---> Iterative Policy Evaluation and Policy Iteration #

Hello! In this blog we will explore Iterative Policy Evaluation and Policy Iteration, using Gridworld as the example program. 

What is GridWorld? It is a well-known concept/program in Reinforcement Learning in which the possibility of moving an object within an environment is illustrated and the program is moving the "player" (also known as an AGENT as discussed elsewhere) around a Map and/or Grid where not all grid positions are available and where one grid represents a "you win" position and one grid represents a "you lose" position. The latter two are also referred to as Terminal States. 

![grid world chart](https://user-images.githubusercontent.com/22970879/42248842-ea5fcf0c-7ee4-11e8-87de-16cc93b80f42.PNG)

Let us explain in more detail what the above image represents:


- Where are the terminal states?
- Where is the "robot"? Row 1 column 3.
- In each state there is a finite choice of actions.
- How many possible states? 11. Because the gray box does not count. 
- The green square is the place you’re going to in order to win. 

- Possible actions: 
      - up, down, left, right
      - (1,1) wall, can't go there
      - (0,3) terminal state (+ 1 reward) AKA "you win"
      - (1,3) terminal state (- 1 reward) AKA "you lose"

----------------------------------------------------------------------------------------------------------------------------------------

TO DIGRESS:

What then is a **State**??? A State is the existing expression of a program or a game. The program moves from State to State by having its current state be shaped by preceding events or user interactions --https://en.wikipedia.org/wiki/State_(computer_science). For example, in Tic-Tac-Toe, in Chess, or even in Solitaire, the program moves from state to state to state based on each previous move by the program itself or by the human player. See below 

![state to state transition tic-tac-toe example](https://user-images.githubusercontent.com/22970879/42248815-c22955a8-7ee4-11e8-9bf1-2fd25e0e9994.png)

For a more complex example, look at the next two pictures/graphs. In it one will see a much more complex system of going from state to state to state which is more typical to be found when trying to represent the workings in a computer program. In this case, changes from state to state to state also create different rewards for all possible moves with each transition.

![state to state transition example graph 07-03-18](https://user-images.githubusercontent.com/22970879/42248826-d27ef750-7ee4-11e8-9132-19529032c7d6.png)

![documenting moving through the graph of 05-31-18](https://user-images.githubusercontent.com/22970879/42248833-df20880c-7ee4-11e8-8aea-7a206d13076d.png)

----------------------------------------------------------------------------------------------------------------------------------------

BACK ON TOPIC:

Having define GridWorld and having defined what a State is, the question then becomes what is **Iterative Policy Evaluation** and **Policy Iteration**. 























