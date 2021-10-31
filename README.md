# Gomoku Player
- - -
**Perfom the Gomoku Player by BFS search to win the game.**

## Using Language
- - -
**Prolog**

## Implementation
* In each step will concern the situation within the next 3 steps.
* Then score those situation and choose the best location in every steps. 
* To follow those rules and extra rules, I set the general restriction to avoid foul.
    * Because first player has a strong advantage, there are some extra rules for black player.
    * Please check [here](https://renju.nu/gomoku-rules/) for more rules information.

## Two stage to construct the player
**To simplify this project, the player can split into 2 parts** 
1. Only Defend  
    * `this part will concern those situations that player has to defense immediately.`
2. Defend + Offense  
    * `Offense part will find the most advantageous location which can lead to win.`
    * `Then combind two part to complete the Gomoku player
 

