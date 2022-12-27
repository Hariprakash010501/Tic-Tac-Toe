# Tic-Tac-Toe
Component Chart:
![image](https://user-images.githubusercontent.com/120704241/209722559-a57f01fd-dbcd-4d4c-a459-4ae1d8e1d11f.png)
Component Hierarchy:
![image](https://user-images.githubusercontent.com/120704241/209723683-0df63d40-a398-4a7a-8c91-bab5092a0c8c.png)
To manage the state in a component, I have used useState which is a hook. The application contains TicTacToe.js which has the parent component TicTacToe. The 3x3 box is generated which is then filled with Xs and Os based on players selection of box. First initialize all the possible combinations which makes the player as winner and after clicking the box whenever any combination matches, Winner is identified or else there may be a tie too and we have to disable the empty box. If the player wants to play the game again for that a button named restart is used. Once restarting the game, all the states are set to default values. To manage props, pass it as an argument and declare prop variables.

Codesandbox link : https://6sb7e3.csb.app/
