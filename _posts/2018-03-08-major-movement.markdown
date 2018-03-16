---
layout: post
title:  "Major Movement"
date:   2018-03-08 17:00:00 +0000
author: Sailesh Patel
---

Firstly, sorry for leaving you for a week. We've had a lot to do so we're such you'll be interested in what we're up to.

## Back Button
After some time, Bruno's finally completed the back button so now players should be able to return to the main menu from the game.

## Artificial Intelligence
Now we've made a lot of movement on this front - we now have two usable AIs thanks to John. We've got an easy and a medium mode, however we currently don't have a hard mode, so John has said that he is going to create some more strategies for the AI to use in order to create a hard mode for single player games.

Vinny's version of the AI has also made some progress with it almost being completed, however he's said that he's got a small bug to fix involving a `NullPointerException`. The bug revolves around the use of a depth search being used, and if there is nothing before `Depth = 0` then a `NullPointerException` is thrown. Vinny's said that he knows what and where the error lies so he has said that he'll have it fixed in no time.

## Networking
The back-end implementation has almost been completed, however according to Charlie, the hardest part about this is thinking through all of the possibilities.

## Animation
We've had a bit more discussion on animation, especially around flipping the counters on the board, where we've said that we need to delay flips, and synchronise the flips to make sure that no other threads are executed while counters are flipped. This is in order to avoid a gamer accidentally clicking on the board while a flip is in progress.

In order to work to this goal, Zak has agreed to meet with James to get the Blender file in order to complete this animation for the flipping.

## Sound Effects
The team also discussed the possibility of sound effects being used. Eastwood has agreed to implement sounds to demonstrate a piece being placed which is being represented as a tapping noise, a piece being rejected using a rejection noise and a piece being flipped using a whoosh sound.

Eastwood also made the background music for Othello, so we've got high hopes for the sound effects for this game.

## Table Background
We also said that we wanted to replace the background with a wooden background. Zak has already found a wooden background we can use and has said that he can implement this very quickly.
