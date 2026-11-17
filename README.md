# Tetris in Python & Pygame
My (pastel &amp; pretty) version of tetris. I created this game as one of my earlier programming projects to improve my Python skills and gain practical experience in developing interactive applications. In addition to the classic Tetris mode, I implemented a second game mode featuring predefined levels and challenges.

![Tetris Gameplay](Gameplay.gif)

# Features
- Two game modes: classic Tetris with increasing difficulty and a challenge mode with predefined playing fields
- Custom movement, rotation, and collision detection algorithms
- Ghost piece indicating the current piece's landing position
- Scoring system, level progression, and preview of upcoming pieces
- Graphical user interface with custom menus and buttons
- Resizable game window with dynamically adjusted graphics

# What I learned
**Object-oriented programming**\
By implementing custom classes for game pieces and buttons, I gained practical experience with object-oriented programming, including classes, attributes, and methods.

**Algorithms and data dtructures**\
One of the main challenges was developing the game's underlying logic. This included representing the playing field as a two-dimensional list and implementing algorithms for movement, rotation, collision detection, and clearing completed rows.

**Event-driven programming**\
Using Pygame, I learned how to handle keyboard and mouse input and implement a continuous game loop to manage user interactions and update the game state.

**Graphics and user interface development**\
Designing the graphical interface introduced me to programmatically rendering visual elements, working with coordinate systems, and converting logical grid positions into screen coordinates.

# What I would do differently today
Looking back at this project, I can identify several opportunities to improve its structure and maintainability.

**Improve organization and naming of variables and functions**\
I would make the dependencies clearer by reducing the use of global variables and organizing related data into dictionaries or classes. Furthermore, my naming conventions were inconsistent, particularly in terms of language and capitalization. 

**Separation of game logic and rendering**\
While I already organized parts of the game into separate functions and classes, I would now aim for a clearer separation between game logic, rendering, and input handling. This would make the code easier to maintain and allow the game logic to be tested independently of the graphical interface.

**Automated testing**\
I tested the game manually during development. Today, I would also consider introducing automated unit tests, particularly for collision detection, piece rotation, and line clearing, to make future changes more reliable.
