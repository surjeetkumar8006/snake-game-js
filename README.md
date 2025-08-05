| DSA Concept            | Implementation Details                                                                                                                               |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Queue (Array)**      | The snake's body is stored as an array, where new elements are added at the front (`unshift`) and removed from the back (`pop`) — just like a queue. |
| **2D Grid**            | The game area is divided into a grid using `x` and `y` coordinates to simulate snake movement on the canvas.                                         |
| **Randomization**      | Food is placed at random positions on the grid using `Math.random()` and rounding logic.                                                             |
| **Searching**          | Self-collision is checked using a linear search through the snake’s body cells.                                                                      |
| **Control Structures** | Direction handling and game-over conditions use `if-else` statements to manage game logic.                                                           |
<img width="817" height="678" alt="image" src="https://github.com/user-attachments/assets/c05cec3f-df5b-439b-9f43-fce131549a1e" />

<img width="1453" height="900" alt="image" src="https://github.com/user-attachments/assets/60917850-7d41-48bf-ae62-d7de44bad9f9" />
