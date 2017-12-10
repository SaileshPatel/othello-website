---
layout: post
title:  "Our Development Journey"
date:   2017-12-06 17:00:00 +0000
author: Sailesh Patel
---

Welcome to Othello G4. Now that you know a bit more about Othello, let's explore our development journey together.

## Origins

Like all great things in life, we have an origin story. Our origin story begins in a lecture room where we were assigned in to a team to build a video game, based on a board game, of our choice. We went away and thought about potential ideas for our video game.

We ended up meeting again and decided on Othello - a strategy based board game, where players win by flipping their opponents pieces, and having the most pieces on the board when the board is full or a stalemate, where a player cannot make a legal move, has been met.

## Getting Started

In order to get started, Arvinder decided to create a preliminary UML diagram of the initial classes John had come up with. This was done in order to get a shared vision of how Othello was going to be designed and implemented. At this stage, we also decided not to write any code until the preliminary UML diagram was complete.

We eventually started programming, and we delegated tasks throughout the classes in order to make sure that the work was spread out and was done concurrently.

Myself and Zak worked on the `Player` class where we attempted to get user input and make moves with this input, while John and Eastwood worked on the `Game` class, where they worked on getting the flow of the game finalised with all of the other classes working together.

Charlie and Arvinder worked on the `GameBoard` class where the logic of the game was stored, meaning that this was an essential part to making sure that the game worked according to the rules of Othello, which can be found [here](https://www.othellog4.com/2017/10/16/welcome-to-g4-othello.html).

Alongside all of these, Bruno and James worked on making sure that the entire project was kept loosely coupled and relatively cohesive with the use of Model-View-Controller concept, in order to make sure that we could easily change our graphics implementation without the need to change our model or controllers dramatically.

We later realised that this was too in depth, so we decided to delegate based on behaviours instead of classes. Myself and Zak ended up breaking down the logic of the game and then giving this to Charlie who worked on implementing this in the `GameBoard` class, while James and Bruno worked on rendering board pieces on our Swing GUI.

John and Vinny meanwhile worked on the design for the hack, which made sure that everybody understood how the hack version of Othello was meant to work and how the different components interacted with one another. Through doing this, the project had an MVC (Model-View-Controller) architecture implemented from start so that

All of this was done in preparation for creating our hack version. The aim of our hack was to prove that the concept behind Othello was achievable. This meant that while our hack was functional, it was far from a finished product.

## After the Hack
After the hack, the team realised that the job that myself and Zak was going was far too simple for the dedication of two individuals, therefore I moved to web development, alongside Eastwood who was already on web development.

This was where a decision to use Jekyll was made, because Jekyll generates static pages, and also allows for the use of front matter, which means that large scale websites can be made more efficiency. Due to the work that James did, we are also able to push any changes to the live site, through a webhook.

Meanwhile, James, Zak and Bruno all started to learn more about LibGDX as a potential replacement for Swing, after going to a mentor meeting. Our mentor gave some suggestions on how we could improve our game in time for the MVP demonstration.

The use of LibGDX is intended to improve the quality of Othello, because in the hack version, Othello is a clunky, out-dated game, which is far from user friendly. This meant that in order to improve Othello, we had to ensure that a good graphics library was chosen.

After the decision on LibGDX, James, Zak, and Bruno all started to learn more about how LibGDX was implemented in order to fully implement a new graphical interface which was smoother and more efficient than Swing.

## Barriers along the way

One of the toughest barriers was implementing the new graphics with the logic of Othello, because it was a steep learning curve to overcome. This was overcome through the work done prior to this, because we had decided to choose a MVC architecture.

This meant that the team was able to implement the graphics without touching the logic of the game, which meant that there was a reduced level of coupling and a higher level of cohesion. This has led to the code being easier to manipulate and change, as well as finding errors, because now the responsibilities are clear, it is easier to locate the relevant classes for future changes.

Another challenge on the game has been creating a generic way to move tokens on the board, because the movement of tokens need to be generic, in order to implement an Artificial Intelligence player.

Although Artificial Intelligence has not been implemented at this stage, the behaviour for moving tokens still needs to be generic, so that the `GameBoard` does not know if a `Player` or an `AI` player at this point.

## What's next?

We are planning to get try and an Artificial Intelligence mode, so that a player can face off against an artificial intelligence player.

We would also be working implementing additional features, such as a tournament mode, where players can play against each other in teams, and a helper feature so that new players can get help on how to play Othello. 
