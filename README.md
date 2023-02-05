# Tour de Force - a trick-based FPS prototype made in Unreal Engine 5

## Overview
Tour de Force is a game where your weapon becomes more powerful as you perform "tricks", such as jumping, staying mid-air, and doing 360's (a full circular motion in a short period of time).

## Download
Windows:

**TODO: insert download link to build**

## How to Play
This game employs standard FPS controls, but only supports mouse and keyboard at this time. The control scheme is as follows:
- WASD for movement
- Spacebar to jump
- Mouse to look around
- Left mouse button to shoot

## Developer Notes

### Background

I had originally made this prototype as a part of my Experimental Gameplay class at the University of Utah's MEAE (Master of Entertainment Arts and Engineering) program. The goal of this class is to come up with "experimental" gameplay mechanics based on a theme, similar to a game jam. We are given one week to come up with a prototype showcasing one or more unique game mechanics based on your own interpretation of the theme. I finished the prototype in one week and decided to make some small additions over the course of the following week.

### Theme and Gameplay

The theme for this project was **spicy**. My interpretation of the word "spicy" was something that is "cool" or "awesome", and I wanted to make gameplay reflect those feelings. I took inspiration from skateboarding and snowboarding games such as *Skate*, *Amped*, and *Tony Hawk's Pro Skater*, taking the general idea of "do tricks to earn points" and combining that with my favorite FPS games like *Halo*, *Call of Duty*, and *Titanfall*. I was reminded of old montages in games like *Call of Duty: Modern Warfare 2* (2009) where players would perform mid-air 360 no scopes with a sniper rifle. 
I wanted to make doing the tricks meaningful, so that the player isn't just performing them for fun (but they can if they want to). 

I decided to make the weapon's power be derived from a meter, which is filled by performing tricks such as jumping, double-jumping, being in the air, and doing a full 360. Each of these tricks will increase the meter until it eventually fills up and the weapon becomes fully powered. If the player does not perform any tricks and the meter is not empty, the weapon's power will gradually decrease.

When the player fires the weapon while it has any amount of charge, the weapon's charge will be reset after that shot has been fired. There is currently no time in between shots.

### Future Improvements
In it's current state, this prototype leaves much to be desired, and I'm hoping to improve upon it so that I can "find the fun". If I continue to work on this game in the future, I'm hoping to add various QOL improvements such as:
- More VFX to make the weapon feel more powerful (camera shake, impact particles)
- Improvements to the trick system so that tricks are more satisfying to perform (combo strings, sound effects, better visual feedback)
- More tricks (somersault, wallrunning, dashing, bunnyhopping(?), etc)
- Diverse weapon behavior based on charge (ricocheting off walls, piercing enemies)

#### TODO: ADD SCREENSHOTS
