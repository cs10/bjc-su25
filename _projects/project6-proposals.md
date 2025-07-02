---
title: Project 4
description: Final Project Proposals
gradescope_assignment_id: 5617918
submission_files:
    - N/A
---

*Version 1.1. Last Updated: 2025-04-02.*

*We highly recommend reading through this spec in its entirety before you begin.*


## Content

[I. Important logistics](#important-logistics)

[II. Introduction](#introduction)

[III. Complexity Guidelines](#complexity-guidelines)

[IV. Required Features](#required-features)

[V. Proposal Contents](#proposal-contents)

[VI. Submission Guidelines](#submission-guidelines)

[VII. Proposal Review: What to Expect](#proposal-review-what-to-expect)

## Introduction

For the final project, you’ll be building a project that you envision in Snap!, completely from scratch (how cool is that!) First, however, you’ll need to submit a project proposal that will be reviewed by a staff member to ensure that your project won’t be too easy or too complex. The proposal should come to about 1-2 pages, single-spaced (before you transfer the information to Gradescope). An example is provided below. 
This proposal is meant to be just an ideas-focused starting point — the spec for the technical requirements of the final project can be found here, and you should reference that as you work with a staff member to ensure that your project idea will meet all requirements.

Please read through this entire spec before writing your proposal. Keep in mind that the project proposal is a REQUIRED element of the final project, and you will receive a 0 on this part of the project if you do not submit your proposal and meet with a staff member for feedback. 

## Complexity Guidelines

Complexity, for your project, basically means “how difficult is it to implement?” and is used as a measurement to ensure that final projects fit a happy medium of not too hard and not too simple, when taking into account both how much you’ve learned and how much time you have. 
If your project idea relies heavily on the following, we recommend you consider alternate projects, or try a suggested workaround:
- Using any primitive block in Snap! Will not count as a feature
- Mainly being a guess-and-check game: This is generally considered too easy since it consists primarily of a - series of if-then-else statements. A number guessing game, for example, would not be complex enough. This might be a good mini-game in a bigger project.
- Data entry: Alone, this might be considered too simple. Often, projects that rely on data entry get ‘bigger’ by having a bigger database. A fix for this would be having the data component be just one part of a bigger project. 
- Robot/AI player: Depending on the game, this could be a good fit, or too complex. An AI player for chess or Go would be too complex. 
- Games like Pong, Tic-Tac-Toe, Guess the word, Hangman, dress-up games, point and click games would not be complex enough and are NOT ALLOWED.
- Games like Angry Birds, Balloons Tower Defense, or Need for Speed would likely be too complex. 
- Games previously implemented in Projects are not allowed (because you’ve already done them).
- Use of generative AI is NOT allowed.

Don’t be worried if you really like a project idea but think it may be too complex, or not complex enough — that’s the purpose of having a proposal and proposal review process, so you can work with a TA to get your project complexity into the right range! 

When considering what your project is, and how you plan to implement it, see if you can figure out a solution or a structure for a solution first, before defaulting to what you’ve seen done before! A few gauges for the complexity of the kinds of solutions we’re looking for are: coming up with logic to check for four-in-a-row in Connect 4 or recreating Flappy Bird in Snap!

Of course, there’s a range of project complexity that falls into the “accepted proposal” range. Here are a few examples.

- [The Chrome Dinosaur Game:](https://chromedino.com/)
    - Feature 1: TWO DIFFERENT OBSTACLES 
        - Randomly generated shrubs and pterodactyls appear on the screen as obstacles.
        - Obstacles NEED to be traveling at different speeds (otherwise project will not be complex enough)
    - Feature 2: The game ends when the dinosaur runs into an object.
- [Mancala:](https://www.mathplayground.com/mancala.html)
    - Feature 1: When a player chooses a group of marbles, those marbles get distributed around the board, picking up more marbles when the last one falls on a non-empty hole
    - Feature 2: Game over when all marbles are in the two goals, winner is the one with more marbles
- [Doodle Jump:](http://poki.com/en/g/doodle-jump)
    - Feature 1: Doodle jumps continuously, moving higher up in the sky as he lands on bouncing platforms that continuously move downwards
    - Feature 2: Game ends when Doodle falls off the screen
- [Bubble Shooter (Difficult):](http://www.shooter-bubble.com/)
    - Feature 1: Computer will generate randomly colored bubbles that players can shoot
    - Feature 2: If the program detects groups of the same color, it will delete them.

Other projects that fit complexity requirements that students have done in the past include: Frogger, Checkers, Flappy Bird, Snake, Chutes & Ladders, various puzzle games, various board games, data science analysis, Battleship, and chatbots.

## Technical Requirements

There are certain technical and style requirements that we want you to be able to demonstrate in the implementation of your final project, regardless of what kind of project you’re doing, which are listed below. For some of the rubric items, you can also mix and match (see rubric for more details). Here is a list of some of the technical requirements you must include:

- Non-trivial list: Your project should include at least one non-trivial list, meaning a list whose function could not be simply replaced with another implementation. Often this can be a tracker of high scores, or part of a game board.
- Custom block/function: Your project should include at least TWO functions that you define yourself. There is no restriction on what type of function this should be, whatever suits your project is what you should do!
- Script/local variable: Your project should include at least one non-global variable. 

## Required Features

On top of the technical requirement your project must have required features. Here is a list of approved features. Your 2-3 features MUST be from the following list. If you are proposing to have a feature that does not fit within the guidelines below, you will need to discuss it with your TA, but it is unlikely to be approved. If you use two of the same features they must be distinct and have unique properties. 

- 2D, Nested lists. The nested list can be a representation of the game board, highscores, positions, or some other structure
- Extensive, dynamic visual display
    - Must include: 
        - At least one background
        - At least two sprite costumes
        - At least one sound
        - A help screen or guide to interact with program / instructions
- Extensive use of OOP in Snap!
    - The main logic of the name would use an OOP structure
- API calls (calls to other programs or websites) - Don’t worry about doing this one; but it’s an option if you’re interested!
- Structures keeping track of important data
    - Examples: Dictionaries, Lists, Trees, Sets
- Complex Algorithm
    - Examples:
        - Merge sort algorithm
        - Determining whether a game is over condition
        - Determining whether a move is valid
        - Determining and displaying the top three (or some number) of high scores
- Extensive use of libraries (in Snap!)
    - Must use at least three different functions for the library imported
    - Or three different libraries imported, and one function each is used. 
- An AI that runs the program/plays game and tries to optimize for winning moves
- Features that DON’T COUNT:
    - Randomization (it’s completely okay to have randomization, but it doesn’t count as a feature)
    - Helper functions
    - Inputs/Outputs and Response/Prompt
        - Example: Games that simply ask a user for a response/prompt to input
    - Broadcasting messages
    - Pointing and clicking

## Proposal Contents 

So now that you’ve got a project idea in mind, it’s time to write about it! The questions you should answer in your project proposal are below. We recommend you draft your answers out on a Google Doc or Word document before submitting them into Gradescope.

- Who are the members of the group? List each group member’s name and SID. You should work in pairs of 2, but if you want to work alone (or in groups of 3) you’ll need to get explicit permission from your TA during the meeting. This is a complicated project, so we very rarely permit students to work solo. 
- What is your vision for the project? Describe the specific project and the major 2-3 features (listed above) you’d like to accomplish. Groups of 2 should list 2 features, groups of 3 should list 3. Please go into detail on this one, even if you think your project is well-known! The clearer you are, the better your TA/tutor will be able to help you adjust the project if it falls outside the optimal range of complexity. 
- How will someone interact with your project? Describe the controls that will be used. For Projects 1-2, the answer to this question would be text input via keyboard. For Project 3, the answer would be keyboard controls/arrow keys. 
- What are the technical elements behind your features? Go into more detail about your preliminary thoughts about how you’ll make the 2-3 features happen. What you come up with here doesn’t have to be exactly what you end up doing, but it should convey how you plan on implementing the project in terms of blocks/functions or computing ideas. For example, Pytris utilizes object-oriented programming to build and abstract different elements of the game.

Here is an [example proposal](https://docs.google.com/document/d/1gy4L6KfyPLT01Xt7acnBNbHwCyI1QR9uXGyin9UWFXc/edit?usp=sharing); it should give a sense of how much detail we want you to go into on the proposal. Feel free to make a copy. 


## Submission Guidelines

You and your partner(s) will submit your project proposal as a group on Gradescope. 

The assignment has the proposal format in it, so your group will need to fill out all of the boxes with your answers to the questions listed in the previous section! Only one person from the group needs to submit. After you submit, please don’t forget to add your partner(s) to the submissions!

![How to add partner to Gradescope](/fa24/assets/images/p6/p6-1.png)

Your project proposal review will take place during the time slot your group signs up for. These slots are during the lab. You need to ensure that you can show up for the time slot you signed up for. 

## Proposal Review: What to Expect

You will explain your project and a staff member will review your project proposal, and either approve or disapprove it. Keep in mind that even if your initial proposal is disapproved, that’s only an indication that that specific version of the project might have been too complex or not complex enough! Your TA/tutor will work with you during the proposal review session to figure out a fix or adjustment to your project idea or suggest other ideas if necessary. 

Regardless of the status of your project proposal (whether it’s unfinished or you’ve changed your mind), you must attend the project proposal review meeting with a TA/tutor. If you are able, please try to attend the lab/OH of the TA/tutor you have your proposal reviewed for the duration of the final project. 
