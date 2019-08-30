# hackerpet Games List

* ### Teaching Your Player (dog, cat, pig, ..) to Use CleverPet
   These games are developed to get your player accustomed with the hackerpet
   hub and are best played in the order below. 
   When the player becomes proficient at the current challenge, switch them
   to the next one!

   |||||
   |:---|:---|:---|---|
   | 0.  | [**EatingTheFood**](./games/000_EatingTheFood) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Help your player get comfortable with the Hub’s sounds and movements. | ![](./games/000_EatingTheFood/EatingTheFood.gif) |
   | 1.  | [**ExploringTheTouchpads**](./games/001_ExploringTheTouchpads) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | A foodtreat is offered, but the player will also earn a reward when they press a touchpad.  | ![](./games/001_ExploringTheTouchpads/ExploringTheTouchpads.gif) |
   | 2.  | [**EngagingConsistently**](./games/002_EngagingConsistently) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Now your player will need to press a touchpad to earn a reward.  | ![](./games/002_EngagingConsistently/EngagingConsistently.gif) |
   | 3.  | [**AvoidingUnlitTouchpads**](./games/003_AvoidingUnlitTouchpads) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Your player must learn that only pressing illuminated touchpads results in success.  | ![](./games/003_AvoidingUnlitTouchpads/AvoidingUnlitTouchpads.gif) |
   | 4.  | [**LearningTheLights**](./games/004_LearningTheLights) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Only one touchpad is illuminated in this challenge.  | ![](./games/004_LearningTheLights/LearningTheLights.gif) |
   | 5.  | [**MasteringTheLights**](./games/005_MasteringTheLights) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Only one lit touchpad, and now your player will need to engage even more consistently.  | ![](./games/005_MasteringTheLights/MasteringTheLights.gif) |
   | 6.  | [**RespondingQuickly**](./games/006_RespondingQuickly) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Your player now has to press two touchpads in a row to solve one puzzle.  | ![](./games/006_RespondingQuickly/RespondingQuickly.gif) |
   | 7.  | [**LearningBrightness**](./games/007_LearningBrightness) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | After the first press, your player will need to choose the brightest touchpad.  | ![](./games/007_LearningBrightness/LearningBrightness.gif) |
   | 8.  | [**LearningDoubleSequences**](./games/008_LearningDoubleSequences) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Your player must press the brightest touchpad accurately twice in a row.  | ![](./games/008_LearningDoubleSequences/LearningDoubleSequences.gif) |
   | 9.  | [**LearningLongerSequences**](./games/009_LearningLongerSequences) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Your player is challenged to complete patterns of up to nine moves in a row.  | ![](./games/009_LearningLongerSequences/LearningLongerSequences.gif) |
   | 10. | [**MatchingTwoColors**](./games/010_MatchingTwoColors) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | The Hub introduces colors, your player’s job is to make all the touchpads match.  | ![](./games/010_MatchingTwoColors/MatchingTwoColors.gif) |
   | 11. | [**MatchingMoreColors**](./games/011_MatchingMoreColors) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | This challenge adds white to the mix, the number of solutions grows exponentially!  | ![](./games/011_MatchingMoreColors/MatchingMoreColors.gif) |


* ### Community Contributed Games
   Anyone can make a game for the Hub! If you'd like to add yours below, just create a pull 
   request to this repository. We'll commit all appropriate games. 
   
   |||||
   |:---|:---|:---|---|
   | 12. | [**hello-animal**](./games/012_hello-animal) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | An introduction to the basics of building hackerpet interactions. | ![]() |
   | 13. | [**OneTwoThreeButtonGame**](./games/013_OneTwoThreeButtonGame) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | This game can be useful during initial training of a player to use the Hub. | ![]() |
   | 14. | [**ColorMatchGame**](./games/014_ColorMatchGame) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | Touching a touchpad toggles it to a different color, the game ends when all the touchpad colors match. | ![]() |
   | 15. | [**WhackAMole**](https://go.particle.io/shared_apps/5d6229549628d800059f724d) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | **(hosted on build.particle.io)** - This is a more "active" game for the Hub that challenges your player's "paw-eye" coordination. | ![]() |
   | 16. | [**WhackAMole**](./games/016_WhackAMole) <br><sup>CleverPet&nbsp;<info@clever.pet></sup> | This is a more "active" game for the Hub that challenges your player's "paw-eye" coordination. | ![]() |


--------


# hackerpet Games

The [CleverPet Hub][cleverpet.io] is a programmable device that lets you
automatically train and interact with other species. It's kind of like a "game
console for dogs and cats".

<p align="center"> <img width="460" src="docs/images/hub1.png"> </p>

The Hub is built on the [Particle][particle.io] platform, which means that the
full suite of tools Particle has built can be used to control the CleverPet Hub.

You can find the main Particle library to control the CleverPet Hub in the
[hackerpet repository][hackerpet_repo] or on the
[build.particle.io][particle_lib] website.

This repository holds all the approved community-submitted games that can be installed 
using hackerpet.

## How to install games

You can find the full list of available games at the top of this document. (a
computer readable list can be found in [games.json][games.json])  
The actual source code of the games can live in one of two places: either on
[build.particle.io][build.particle] or in this repository under the
[games][games_folder] folder.

Once you've picked your game and clicked on its link you can end up:
*  on build.particle.io  
   Now you just click the `Copy This App` button and then hit the lightning bolt
   icon in the top left to install the game on your hub.
*  in the games folder in this repository  
   To install this game you'll have to first clone or download this repository.
   Then you can use install the game to your Hub using one of:
   1. [particle-cli][particle_cli], 
   2. [Particle IDE (DEV}[particle_dev] (slightly easier to use), or
   3. [Particle workbench][particle_vsc] (more sophisticated) for Visual Studio Code

## How to submit games

You can add your own game to this list by simply submitting a pull request (PR) in
this repository.
A few guidelines for assuring a quick PR approval:
* Please make sure you've tested the game and that you've succeeded at training a player to play it! 
* Please make sure that the game/app isn't a duplicate of others already here
* In your PR, make sure you update both this file and [games.json][games.json]
* Please submit one game per PR :)
* Ensure you've already completed the [CleverPet Individual
Contributor License Agreement (CLA)][CLA], which is based on the Google CLA. 

If you want to also include your source in this repository, you can make a new folder 
under the [games folder][games_folder] named after your game. The directory structure of
your game should follow the standard Particle project structure. You can see an
example of the structure in the [`hello-world`][hello_world] game folder.

## Definitions

In the hackerpet libraries words such as "challenge", "interaction" etc. are used
in specific ways:

*  **Player:** Any dog, cat, person, or other animal who is playing with a Hub.

*  **Foodtreat:** A food reward. E.g., a dog treat, cat treat, or piece of
   kibble.

*  **Report:** A single row of data describing everything that a player did
   during an interaction.

*  **Interaction:** A presentation of lights, sounds from a Hub, and the
   corresponding responses of a player, ending with a report. Nearly always, an
   interaction begins with the Hub doing some things, the player doing some
   things in response, and then the player getting some feedback as to whether
   they did the right thing.

*  **Challenge:** A series of one or more interactions, usually of progressively
   increasing difficulty, and often designed to teach the player a particular
   skill. *Example: the Responding Quickly challenge where the pet has to go
   through several iterations of pushing multiple lit up buttons and getting
   foodtreats.*

*  **Challenge set:** A series of challenges, such as the collection of 13
   original CleverPet challenges.

*  **Level:** A stage of difficulty within a given challenge. Lower levels are
   easier, and each challenge usually has a fixed number of them.

*  **Game:** A fuzzy term, currently without precise technical definition,
   sometimes used interchangeably with "challenge", but which may consist of
   multiple challenges.


[hub]: https://github.com/CleverPet/HackerPet/blob/master/docs/images/hub1.png "Hackerpet hub"
[cleverpet.io]: https://clever.pet/ "CleverPet website"
[hackerpet_repo]: https://github.com/Cleverpet/HackerPet/ "hackerpet repository"
[particle_lib]: https://build.particle.io/libs/hackerpet/0.2.2/tab/hackerpet.cpp "hackerpet library"
[particle_cli]: https://docs.particle.io/tutorials/developer-tools/cli/ "Particle CLI"
[particle_dev]: https://docs.particle.io/tutorials/developer-tools/dev/
[particle_vsc]: https://www.particle.io/workbench/ "Particle workbench"
[build.particle]: https://build.particle.io "Particle build environment"
[games.json]: ./games.json "JSON games list"
[games_folder]: ./games/ "games folder"
[hello_world]: ./games/hello-world "Example game"
[particle.io]: https://particle.io/ "Particle website"
[CLA]: https://docs.google.com/forms/d/e/1FAIpQLSeXAajtFZpQ0VtHK2APtfzrA5w8DMNagJhCfLVr6h9lCQgj1g/viewform "Contributor License Agreement"
