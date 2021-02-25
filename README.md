# Cursed City AI Companion App

_A mostly reasonable approach to Warhammer Quest Cursed City_

To run the app [Click Here!](https://msjoegreen.github.io/ccaicompanion/CCBehaviours.html):

**Note**: This app assumes you own and use Warhammer Quest - Cursed City by Games Workshop. This app is a companion app and not a replacement for the game or it's rules and have never been intended as such.

**Note 2**: The app is currently in a non-working state as we are yet to see the game and the rules that are required for this app to be setup properly.

## Table of Contents:

1. [Introduction](#introduction)
1. [How to Use](#how-to-use)
1. [Making Changes](#making-changes)
   1. [Adding new Quests](#adding-new-quests)
   1. [Adding more Hostiles](#adding-more-hostiles)
1. [Technical Documentation](#technical-documentation)

## Introduction

This app is a companion to the boardgame Warhammer Quest - Cursed City from Games Workshop.

It is designed to help with rolling dice and perform the lookups needed for each individual hostiles behaviour rolls, also the end turn event rolls and result lookup can be performed in this app.

you can find an online runnning version of the app [here](https://msjoegreen.github.io/ccaicompanion/CCBehaviours.html):

you can also find the git version of the code [here](https://github.com/msjoegreen/ccaicompanion):

**[⬆ back to top](#table-of-contents)**

## How to Use

The Cursed City AI Companion App is easy to use but here is a quick rundown on how to use it anyway.

when loading the Cursed City AI Companion App you are greated with a page with only a few options.

1. You can select the which quest you and your friends are currently on by the selecting the quest in the "Select Quest" dropdown list.<br>
   When the quest have been selected you can now push the "Roll Event" button to the right of you selection.<br>This will then perform a dice roll and present you with a dialog box showing you the roll result and what event that resolves to.

1. You can also select which hostiles you are facing in quests current mision<br>Simply select the appropiate hostiles from the "Select Hostiles" dropdown list (you can sellect multiple hostiles by holding down the shift button while selecting)<br>

**[⬆ back to top](#table-of-contents)**

## Making Changes

Adding changes to the app either by adding new quests and ore more hostiles is not that hard but as the app is designed to a single html page with both markup and client side scripting making it comlpetely independant and able to run in a browser with no internetconnection after load, it can be a little dauntig to find your way aroiund the code.

This section will guide you through what you need to change or add when customising the app.

Before following the guides it is suggested that you visit the section with [Technical Documentation](#technical-documentation) to get a better understanding of the design of this app.

### Adding new Quests

Info will follow after release

### Adding more Hostiles

Info will follow after release

**[⬆ back to top](#table-of-contents)**

## Technical Documentation

The app is developed as a single page app consisting of both HTML and javascript in the same file.

### Script Section

### Html-body section

**[⬆ back to top](#table-of-contents)**
