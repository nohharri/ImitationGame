# Imitation Game
## Introduction
Twilio based text messaging game inspired by the Turing test and the movie Imitation Game

Imitation game is a game loosely based on the Turing test and the movie Imitation game. 

This was made to better understand Twilio for an upcoming interview. 

The Turing test was a test developed by Alan Turing to see if a machine could be indistinguishable from a human being. The basic format of the test is Player C determines whether player A or B is human. If the machine can convince Player A that they are human, the machine has passed the Turing test.

## How to Play
The game is structured around guessing who is pretending and who is the actual person. There are three main roles: **pretender, actual, and guesser.** A topic will be given for the game and users must converse about that topic until the guesser is ready to make a guess. The pretender is on their own team and the actual and guesser must work together to beat the defender.

**Disclaimer: This game can only be played between friends due to the nature of the game being structured around familiarity and personality.

### Pretender
The pretender's role is to convince the guesser that they are the actual. This is done through personality imitation. The pretender is given the most information, such as the identity of the guesser and actual.

### Actual
The actual's role is to convince the guesser that they are who they say they are such that the pretender has not deceived the guesser. Teh actual has the least amount of information. The texts given to them will be ambiguous, so that they will not know who is sending as the guesser and who is sending as the pretender.

### Guesser
The guesser must attempt to guess whether user 0 is the pretender or if it is user 1. Texts will be given to the guesser with identities only known as user 0 and 1. The guesser can then guess at anytime to see if the person is telling the truth.

## Setup
* To initialize a new game, simply type new to the number: **18666144247**
```
new
```
* This number will be how the game is played through.
* Due to the prototypical state of this project, there is no database storing this information. This is all done through a JSON file. Three users must be manually entered to play. ./variables.json stores this information.
* Users must also be registered by their caller ID in order to play. Contact nohharri@umich.edu if you would like to be added to this list with your phone number. You will be sent a validation code.

https://www.twilio.com/console/phone-numbers/verified
