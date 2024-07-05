<h4 align=center>NYU Tandon School of Engineering<h4>
<h3 align=center>CS-UY 3113 Spring 2024</h3>
<h1 align=center>Project 3: <em>Lunar Lander</em></h1>
<h3 align=center><em>Due: 11:59pm, Saturday, March 9th, 2024</em></h3>

### Submission instructions
1. You _must_ use delta time, the `Entity` class, and fixed time steps in this assignment.
2. You should submit your homework on [**Brightspace**](https://brightspace.nyu.edu/d2l/lms/dropbox/admin/mark/folder_submissions_users.d2l?db=793153&ou=354438).
3. You should also push that same version to your GitHub account. Note that any commits done after the deadline will be ignored.
4. You only need to submit the github repo link to your homework.
5. Do not use any OpenGL functionality that we have not learned in class.
6. All of your `.cpp` files should contain a header comment block as follows:

```c++
/**
* Author: [Your name here]
* Assignment: Lunar Lander
* Date due: 2024-07-13, 11:59pm
* I pledge that I have completed this assignment without
* collaborating with anyone else, in conformance with the
* NYU School of Engineering Policies and Procedures on
* Academic Misconduct.
**/
```

***No late submissions will be accepted***.

### Sections

#### _Requirements_

1. [**Player Falls With Gravity (25%)**](#requirement-1-player-falls-with-gravity-25)
2. [**Moving With Acceleration (25%)**](#requirement-2-moving-with-acceleration-25)
3. [**Mission Failed (25%)**](#requirement-3-mission-failed-25)
3. [**Mission Accomplished (25%)**](#requirement-4-mission-accomplished-25)

#### _Tips_

1. [**Common Issues**](#common-issues)
2. [**Extra Credit**](#extra-credit)

### Requirement 1: _Player Falls With Gravity (25%)_

- The player should fall according to an acceleration of gravity of your choosing. Traditionally, Lunar Lander games use a small value for their acceleration of gravity to simulate outer space, but yours can be whatever if it makes sense for your theme.

### Requirement 2: _Moving With Acceleration (25%)_

- Moving to the left and to the right should change the player's _acceleration_ (_not_ their velocity). In other words, when the player lets go of the key, the "ship" should still drift for a bit before coming to a stop.
- **Do not directly update `m_movement` (or your equivalent) in order to achieve this effect**. You should only change the values contained in `m_acceleration`.

### Requirement 3: _Mission Failed (25%)_

- If the player touches anywhere in the map that they're not supposed to, show a "mission failed" message on screen, ending the game.

### Requirement 4: _Mission Accomplished (25%)_

- If the player touches one of the platforms necessary to win the game, show a "mission accomplished" message on screen, ending the game.

### _Common Issues_

- Focus on getting your "ship's" movement first. This is by far the most difficult part of the project. Once you get this mechanic to work, you can start building the rest of the world.
- Check out the [**original Lunar Lander**](https://youtu.be/McAhSoAEbhM) for inspiration and ideas of how the gameplay should feel. Its UI is actually pretty helpful in telling you what the values of its movement, velocity, and acceleration are/might be.

### _Extra Credit_

- Add a "fuel" mechanic to the game. 
    - When the player is pressing a key to change the acceleration, your game should use up some of this fuel. 
    - Once your fuel has run out, pressing a key to change the acceleration should no longer work.
