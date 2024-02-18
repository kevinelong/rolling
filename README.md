# rolling rocks simulation
Rules:
    Rocks roll left to right.
    Walls do not roll.
    Walls stop rocks from rolling.
    Stopped rocks stop their neighboring rocks from rolling.
    
    O is a rock
    X is a wall
    . is empty space

    The world is a series of symbols that change over time.
    Time loops through a series of cycles until they stop changing (become stable). (at most 8)

    here are some initial inputs and final output (we are omitting the states in between)
    "O......X" becomes "......OX"
    ".O.X.O.X" becomes "..OX..OX"
    "OOO..XO." becomes "..OOOX.."
    
TASK:
  define a function that:
    1. receives a text string as an initial state
    2. loops until no more changes occur
    3. changes the string according to the rules during each loop
    4. returns and prints out the final state string
    5. bonus points for testing all three examples

Prerequisites:
  1. boolean expressions (true/false) e.g. 2+2 == 4 is true
  2. using square brackets to access and modify array list values e.g. "O" == text[0]
  3. understanding flow control using loops and conditional statements (ifs) with logical expressions
  4. creating functions that receive external arguments as input parameters and return results e.g. add(p1, p2) => p1 + p2
