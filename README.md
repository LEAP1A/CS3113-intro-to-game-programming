<h1 align=center>CS3113 <em>Introduction to Game Programming</em></h1>

<h2 align=center>New York University Tandon School of Engineering</h2>

<p align=center>
    <a href="https://www.learncpp.com/"><img src="https://img.shields.io/badge/Language-C%2B%2B-5E97D0"></img></a>
    <a href="https://developer.apple.com/xcode/"><img src="https://img.shields.io/badge/IDE%20(MacOS)-XCode-lightgrey"></img></a>
    <a href="https://code.visualstudio.com/"><img src="https://img.shields.io/badge/IDE%20(Windows)-Visual%20Studio-blue"></img></a>
    <a href="https://www.opengl.org/"><img src="https://img.shields.io/badge/Library-OpenGL-yellow"></img></a>
</p>

---

### _Sections_

1.  [**Lecture Notes**](#lecture-notes)
2.  [**Instructor**](#instructor)
3.  [**Class Information**](#class-information)
4.  [**Description**](#description)
5.  [**Objectives**](#objectives)
6.  [**Computer/Software Requirements**](#computersoftware-requirements)
7.  [**Grading Scheme**](#grading-scheme)
8.  [**Deadlines**](#deadlines)
9. [**Getting Help and Slack**](#getting-help-and-slack)
10. [**Moses Center Statement of Disability**](#moses-center-statement-of-disability)
11. [**Academic Integrity**](#academic-integrity)

---

### _Lecture Notes_

1. **Week 1**: The basics
    1.  [**Introduction**](lectures/introduction/)
    2.  [**Triangles**](lectures/triangle/)
2. **Week 2**: Moving in video games
    1.  [**You're getting old, Matrix**](lectures/matrices/)
    2.  [**Transformations**](lectures/transformations/)
3. **Week 3**: Applying art to our games
    1.  [**Delta Time**](lectures/delta-time/)
    2.  [**Textures**](lectures/textures/)
4. **Week 4**: Player input and basic collision detection
    1.  [**Player Input**](lectures/player-input/)
    2.  [**Collision Detection**](lectures/collision-detection/) 
5. **Week 5** Sprite Animation and Text and The Entity Class: 
    1.  [**Sprite Animation and Text**](lectures/sprites-and-text/)
    2.  [**Entities**](lectures/entities/)
6. **Week 6**: Physics 1 and Physics 2
    1. [**Physics: Gravity**](lectures/physics_1/)
    2. [**Physics: Colliding with Different Kinds of Entities**](lectures/physics_2/) 
7. **Week 7**: Music, sound effects, and basic enemy AI
    1. [**Music and Sound Effects**](lectures/sound-fx/)
    2. [**Basic Enemy AI**](lectures/enemy-ai/)
8. **Week 8**: Map and stage building
    1. [**Tilesets and Tilemaps**](lectures/maps/)
    2. [**Scenes**](lectures/scenes/)
9. **Weeks 9**: Special effects
    1. [**Effects**](lectures/fx/)
    2. [**Shaders**](lectures/shaders/)
10. **Week 10**: [**Playtesting and publishing your game**](lectures/playtesting/)
<!-- 12. **Week 12**: NES game development and playtesting your final projects -->
<!-- 13. **Week 13**: Presenting your final projects -->

<!-- 10. **Week 10**: Intro to 3D
    <!-- 1. [**Intro to 3D**](lectures/SDL3D/SDLProject/)
    2. [**3D Models**](lectures/3d-models/SDLProject/) -->
<!-- 
21. [**3D Levels: Floors, Movement, and Collisions**](lectures/3d-levels/SDLProject/)
22. [**Billboards**](lectures/billboards/SDLProject/) -->

<sub>Released on each lecture day before class.</sub>

<br>

### _Instructor and Course Assistant_

[**Sebastián Romero Cruz**](https://github.com/sebastianromerocruz)  _(They / Them)_

| **E-Mail**                                  | **Office Hours**                                                                                                     |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| [**sebastian.romerocruz@nyu.edu**](mailto:src402@nyu.edu) | [**calendly**](https://calendly.com/profromerocruz) |

[**Wesley Zhuang**](https://github.com/Wea3el)

| **E-Mail**                                  | **Office Hours**                                                                                                     |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| [**wz2445@nyu.edu**](mailto:wz2445@nyu.edu) | Monday Tuesday 10:30 - 12:00 pm at 8th floor 370 Jay Street  <br> Friday 10:00 - 12:00 online|


<br>

### _Class Information_

- **Pre-Requisites**: [_**Data Structures and Algorithms**_](http://bulletin.engineering.nyu.edu/preview_course_nopop.php?catoid=15&coid=36541) (C- or better)
- **Credits**: 3

### _Description_

A programming intensive introduction to the creation of computer games. Using mostly two-dimensional 
sprite-based programming, we examine and experiment with animation, physics, artificial intelligence 
and audio. In addition, the course explores the mathematics of transformations (both 2D and 3D) and 
the ways they may be represented.

<br>

### _Objectives_

This class is, fundamentally, an exercise in building your own game engine. You will learn about vectors, coordinate systems, sprites, collisions, physics, audio and handling input. This will all be done with C++ programming and utilizing the SDL (Simple DirectMedia Layer) libraries along with OpenGL. You will be able to create simple 2D games in your engine.

<br>

### _Computer/Software Requirements_

You need to use either a Mac or Windows computer. You do not need a powerful machine as we are
not writing anything super complicated. For Mac users, you’ll be using Xcode. For Windows, you will
be using Visual Studio. These are both freely available.

You will also need a [**Github**](https://github.com/) account!

<br>

### _Grading Scheme_

| **Item**                                                                | **Percentage** |
|-------------------------------------------------------------------------|----------------|
| **_Project 1_**: [**Draw a Simple 2D Scene**](assignments/project_1.md) | 10%            |
| **_Project 2_**: [**Pong**](assignments/project_2.md)                   | 10%            |
| **_Project 3_**: [**Lunar Lander**](assignments/project_3.md)           | 15%            |
| **_Project 4_**: [**Rise of The AI**](assignments/project_4.md)         | 25%            |
| **_Project 5_**: [**Students' Choice**]()                               | 30%            |
| **_Classwork_**                                                         | 10%            |

- Every assignment will have an "extra credit" portion. This will **add 5% to your final grade** at the end of the semester if you complete the extra credit portion of **at least 3 of the projects**. While 5% may not seem like a lot, it can mean the difference between two letter grades. This can be especially helpful later in the semester, when the projects become longer and more complex.

- Classwork is based on 5-6 group assignments to be completed, as the name implies, during class. In order to get credit for these, you will need to:
    1. Be there.
    2. Complete the assignment with your team _before_ the end of class.
    3. Complete the assignment using only structures learned in class.
    4. Ensure that at least one person in your team shows the finished solution to the professor.

As for your final letter grade, the following scale will be used:

| **Letter Grade** | **A**  | **A-** | **B+** | **B** | **B-** | **C+** | **C** | **C-** | **D+** | **D** | **F** |
|------------------|--------|--------|--------|-------|--------|--------|-------|--------|--------|-------|-------|
| **Range**        | 93-100 | 90-92  | 87-89  | 83-86 | 80-82  | 77-79  | 73-76 | 70-72  | 67-69  | 60-66 | 0-60  |

<br>

### _Deadlines_

- All projects are due at **11:59pm on Saturdays**.
    - Due by 11:59pm means your project was successfully uploaded _by that time_. This means that the version to be graded must be uploaded in both Brightspace and GitHub at that time.
    - Start uploading your project at least an hour before the deadline.
    - Projects received **1 minute late** are considered to be **a day** late.

- If there are any issues with uploading your project, you must email me **before the due date**.
    - While I check email regularly, do not expect a response over the weekend or close to deadlines.
    - Your code must compile. Code that does not compile will receive a grade of 0.
    - Late projects will have 10 points deducted per day. Late projects will not be accepted after 2 days.

All work is to be done on your own. There are no group projects.
**There is no additional extra credit** in this course and the grades are **not curved**.

#### Project Schedule

| Project                 | Release Date | Due Date      |
|-------------------------|--------------|---------------|
| **Simple Scene**        | 02/07        | 02/15         |
| **Pong**                | 02/14        | 03/01         |
| **Lunar Lander**        | 02/28        | 03/15         |
| **Platformer**          | 03/14        | 04/05         |
| **Students' Choice**    | 04/04        | 04/25 & 05/02 |

<br>

### _Getting Help and Slack_

If you are emailing me for help with your projects, upload your entire project to github and email me with the link 
(I need to see everything so I can help you). Do not email screenshots of your code. 

**Slack Server**: We will be using Slack to answer quick questions that you may have about the course throughout the 
summer; the join link will be provided during the first day of class. While I’m usually pretty lax in terms of behavior in our server (see: #off-topic), this server is still a university environment and should be treated as such. Be respectful to me, your course assistant, and to your fellow students. Please adhere to the following rules:

- Do not post your homework assignment code, or anybody else's, on this server. Doing so will have you automatically banned and flagged for plagiarism. You may, however, share small code blocks that don’t give away your implementation in order to ask questions.

- Please use your real first and last name as your name for easy identification.

- While we aim to be as active as possible on this server, we may not always have time to respond to a question. Please respect the team’s time as you wait for somebody to answer your question. As a student of this class, you should aim to try to answer your classmates' questions as well, instead of waiting for me to answer them every single time.

- This is a productivity server. While we encourage a relaxed atmosphere, let's stay on topic. For absolutely necessary off-topic content (it happens), post in #off-topic.

- Use #concepts-help to ask questions that pertain to the lecture material in general (i.e. not specific to a project).

- Use #projects to ask questions that pertain to the project concepts in general.

- Do NOT use this server to rant about your performance in the class. This is a professional environment, and so such behavior will result in a ban. If you would like to discuss your grades, schedule office hours with me.

- You may not invite any people outside of our class into this server.

<br>

### Moses Center Statement of Disability

If you are a student with a disability who is requesting accommodations, please contact New York University’s Moses Center for Students with Disabilities (CSD) at 212-998-4980 or **mosescsd@nyu.edu**​. You must be registered with CSD to receive accommodations. Information about the Moses Center can be found at [**www.nyu.edu/csd**](**www.nyu.edu/csd**)​. The Moses Center is located at 726 Broadway on the 3rd floor.

<br>

### Academic Integrity

NYU School of Engineering Policies and Procedures on Academic Misconduct [**Student Code of Conduct**](https://engineering.nyu.edu/life-tandon/student-life/student-advocacy/student-code-conduct).

- **Introduction**: The Tandon School of Engineering encourages academic excellence in an environment that promotes honesty, integrity, and fairness, and students at the Tandon School of Engineering are expected to exhibit those qualities in their academic work. It is through the process of submitting their own work and receiving honest feedback on that work that students may progress academically. Any act of academic dishonesty is seen as an attack upon the School and will not be tolerated. Furthermore, those who breach the School’s rules on academic integrity will be sanctioned under this Policy. Students are responsible for familiarizing themselves with the School’s Policy on Academic Misconduct.

- **Definition**: Academic dishonesty may include misrepresentation, deception, dishonesty, or any act of falsification committed by a student to influence a grade or other academic evaluation. Academic dishonesty also includes intentionally damaging the academic work of others or assisting other students in acts of dishonesty. Common examples of academically dishonest behavior include, but are not limited to, the following:

    - **Cheating**: intentionally using or attempting to use unauthorized notes, books, electronic media, or electronic communications in an exam; talking with fellow students or looking at another person’s work during an exam; submitting work prepared in advance for an in-class examination; having someone take an exam for you or taking an exam for someone else; violating other rules governing the administration of examinations.

    - **Fabrication**: including but not limited to, falsifying experimental data and/or citations.

    - **Plagiarism**: intentionally or knowingly representing the words or ideas of another as one’s own in any academic exercise; failure to attribute direct quotations, paraphrases, or borrowed facts or information.

    - **Unauthorized collaboration**: working together on work that was meant to be done individually.

    - **Duplicating work**: presenting for grading the same work for more than one project or in more than one class, unless express and prior permission has been received from the course instructor(s) or research adviser involved.

    - **Forgery**: altering any academic document, including, but not limited to, academic records, admissions materials, or medical excuses.
