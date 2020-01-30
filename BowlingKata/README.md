* The task is to implement a scoring system for tenpin bowling.
* The task is purely code based. No UI code needs to be added
* We will follow a Test Driven Development (TDD) approach
   * The rules are as follows:
   * The game is divided into 'Frames'. At the end of each frame, the bowling alley will reset all pins that have been knocked down
   * Usually, each player will have 2 throws in each frame. (They may have 3 in the last frame)
   * If the player knocks down fewer than 10 pins, their score will be simply the number of pins that they knocked down
   * If the player knocks down 10 pins with 2 throws (e.g. they knock down 3 on the first throw & 7 on the next), they score a 'Spare'. The score is 10 + whatever the score of the next throw is (this throw will also be part of the next frame)
   * If the player knocks down 10 pins with 1 throw, they score a Strike. The score is 10 + whatever the score of the next throw is (this throw will also be part of the next frame)
   * In the final frame of the game the player may throw 3 balls if they score 10 in the first two throws
   
* There is no requirement to provide intermediate scores
* There is no requirement to cater for multiple players
