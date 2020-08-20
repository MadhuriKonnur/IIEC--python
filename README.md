# IIEC--python
Outcome of Day 4 - Specialist in Python initiative by IIEC RISE mentored by Mr. Vimal Daga

Problem Statement : Convert the OS based program into a menu or choice driven program using Python script. This will parse the user given query as a text to identify the right application to launch. 

As  this  program is user centric, there is a need to understand generic human input and open the right application. This gives a flexibility for the user not to be specific about the wordings or characters or group of words or even the order of words. 

Different user can input same thing in different way
         e.g. "please lauch DB " or "DataBase please"

        Here I tried to match with certain choices.

2. If user enter invalid  or the application doesnt exist, then user can re-try his/her choice again by giving  preferred input.

3. At any time user wants to exit out of the script/program, they can type quit or exit and the python script exits.

Implementation: 

I have used 3 applications from the Ubuntu default app library which are Google Chrome, SQLite DB Browser, Gedit. However other applications under /usr/bin location can also be added to the choice list.

I have written the whole prohram as a function so that it can be called easily or can be recursively used for multiple sets of applicatins as a future enhancement. 

This program can be executed both on any jupyter consoles or from any commandline terminals with pythong installed and configured properly.

Please provide your valuable feedback for improvement.
