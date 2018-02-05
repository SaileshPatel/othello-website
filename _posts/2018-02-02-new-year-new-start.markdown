---
layout: post
title:  "New Year, New Start"
date:   2018-02-02 17:00:00 +0000
author: Sailesh Patel
---

Welcome back! 

After a wonderful, well-earnt Christmas break, we are back to work on making Othello bigger and better! 

If you've had chance to play Othello over Christmas, thank you so much! We've loved making this game so far and we hope that you'll have fun playing this game!

## Updates!

As some of you might know, we had a showcase near Christmas time, where we demoed Othello in front of a room full of our peers and several experts who were able to provide us with feedback on our progress so far. 

Now that we've had time to meet-up and have two group meetings, we've decided that we need to focus on several items in order to take Othello from being an MVP to a fully-fledged software product. 

### Development Process
After our first meeting of the year, we decided that we needed to formalise our entire development process. This is because we are planning to take on a lot more tasks throughout the rest of this year, which means that communication is vitally important. 

This is why the entire team have decided to follow a Kanban-based process, where we have a Trello board with tasks to do. This means that all team members know what needs to be done. Following this, team members can pick and choose tasks to do, meaning that tasks can be done on an agile basis. 

It also reduces the backlog of tasks to do, as prior to this, we relied on ad-hoc communication via a WhatsApp group chat, which led to miscommunication over the ownership of tasks as well as priorities.

### Board Dimensions 

In our first meeting, the topic changing the size of the board came up again.

The idea behind this is to make the game more customisable to players, by allowing them to set the size of the board. This means the game can be longer or shorter than the initial 8x8 board. 

Charlie has decided to pick this task up, from the Trello board, and he stated his desire to do so. Charlie also came up with an extension of this idea, whereby the actual shape of the board could change as well as the size. Charlie so far has worked on some experimental features to try and find out how this could be implemented.  

### Game States

Another topic brought up in our first set of meetings were game states. Although our game does end when a player has won, we are aware that we haven't added states yet. 

Some initial states discussed included a final state, which states who won the game or whether the game ended up in a stalemate (a low, but still possible scenario), as well as states for pausing and reloading the game from either paused or saved states. 

While, this is primarily the responsibility of the backend of the game, some elements of this such as the presentation of the final game state information, belongs to the graphical team. 

Charlie has once again agreed to create the final state, while Zak has agreed to implement a feature to reduce the volume or mute the background music. In addition to this, the graphics team are all working on an options menu, which will allow for the game to be paused and/or saved in the future. 

### Graphics 

One of the high priority items we want to desperately implement are higher quality graphics. At the moment, Othello is a 2D game, while we want to upgrade this facility. 

While we have stated in the past that we wanted to implement 3D graphics, several members of the team mentioned that 2.5D graphics might be the way forward. This is because of the nature of Othello, being a very low-intensity game, which is primarily board-based, where counters are moved. 

The entire graphics team (James, Bruno and Zak) are currently exploring how these new improved graphics could be implemented, as well as how these adaptations could be made efficiently to allow for future mobile adaptation. 

### Artificial Intelligence

In the second meeting of the year, Aleksander brought a simulation of a Monte Carlo based Articial Intelligence based system, which is a brute-force algorithm. He then demoed this simulation to the rest of the team and explained how we could implement this within our existing game. 

During our meetings, the rest of the team brought up the use of heuristics to allow the artificial intelligence algorithm to be improved over time. One of the heuristics brought up was the use of corner locations on the board and how this gives a player an advantage. 

Aleksander agreed to go away and re-create these simulations with this heuristic added in, while consulting with John and Vinny on how to implement this within the game as it exists at the moment. 

Vinny & John also brought up an alternative algorithm for an artificial intelligence algorithm he has been developing, based on the number of available moves from a location on the board. He built this algorithm up from a function already implemented, which list a number of legal moves that can be made from a point on the board. 

As a result of this, Vinny also agreed to explore this algorithm a possibility. 

### Testing 

Finally, one of our improvements is testing. Our testing and quality assurance processes in the past have either been very ad-hoc or non-existant due to our overall mission, which was to create a minumum viable product. 

Our mission from this point onwards has now changed to creating a high quality Othello game. 

This means that our use of testing has become more important, as John noted in our first meeting of the year. 

At the moment, only stubs for some automated unit tests have been written by Vinny in JUnit, however in the future, we are planning to have more formal testing, including having other people write tests and execute these tests in order to avoid a bias. 

We also plan to use exploratory testing far more, to explore whether functional requirements of the game have been met, because it is difficult to explore this using scripted tests. 

We do still plan on utilising scripted tests to test smaller units of code, as well as using 'tours' where several hours are dedicated to playing the game, either based on a pre-defined script of moves or just exploratory moves to find bugs where they may lie. 

At the current time, Aleksander found some bugs, with the game, as a result of exploratory tours of the game, which John and Aleksander have agreed to fix. 

Vinny, who has been working on some unit tests for several classes, has agreed to continue working on these classes. 