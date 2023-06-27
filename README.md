# Snake-Game
This app was created as a group project for our Grade 12 Computer Science class, ICS4U0. It is a themed remake of the infamous Snake Game, with minor added features such as the ability to change skins. This can be considered an intermediate level project with the use of methods and base adapters alongside basic logic.

### Game Description:
This is a grid game where the snake starts out at a length of 3 tiles and can moved around with the arrows shown on the screen. As the snake crosses an apple, it grows in size. If the snake's head touches the sides of the grid or hits itself, the game ends. The score depends on the number of apples eaten.

### Basic Logic:
The game essentially uses a giant array to store values for the status of each cell. Depending on whether the cell is empty, has an apple, or contains parts of the snake, the value of that cell in the array varies with different integers. A separate array is sent to a base adapter to control the cell colors constantly.

### Demo:
View the demo for this app [here.](https://youtu.be/BOKc90Mj1Ao)

### Tools Used:
- **Android Studio** - The tool used to develop the app
- **Java** - The programming language used to code the logic of the app
- **Base Adapter** - Class used to control the color of each cell on the grid

### Collaborators:
- [@mdola19](https://github.com/mdola19) - Coded the logic for the game screen
- [@thuvaragan25](https://github.com/thuvaragan25) - Designed the UI and integrated all features for final app

