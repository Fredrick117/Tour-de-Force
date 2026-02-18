# Tour de Force - a trick-based FPS prototype made in Unreal Engine 5

## Overview
Tour de Force is a game where your weapon becomes more powerful as you perform "tricks", such as jumping, maximizing air time, and doing 360's.

## Download
See the [releases](https://github.com/Fredrick117/Tour-de-Force/tree/main/Downloads) page _(currently Windows only)_

## How to Play
Controls:
- WASD for movement
- Space to jump
- Mouse to look around
- Left mouse button to shoot

Your weapon's power is displayed as a bar in the top left of the screen. The more full this bar is, the more damage your shots will do.

<img width="985" height="99" alt="image" src="https://github.com/user-attachments/assets/712c8b95-eba3-4a3d-adf1-9d3cb7bc6d4a" />

To actually fill the bar, try performing some aerial maneuvers, like jumping, double-jumping, and 360s! Some maneuvers will increase the weapon's power faster than others.

![360](https://github.com/user-attachments/assets/5caade4d-7143-4bf3-87e8-3aa7cf7d35d1)

## Background

I had originally made this prototype as a part of my Experimental Gameplay class at the University of Utah's MEAE (Master of Entertainment Arts and Engineering) program. The goal of this class is to come up with "experimental" gameplay mechanics based on a theme, similar to a game jam. We are given one week to come up with a prototype showcasing one or more unique game mechanics based on your own interpretation of the theme.

## Theme and Gameplay

The theme for this project was **spicy**. My interpretation of the word "spicy" was something that is "cool" or "awesome", and I wanted to make gameplay reflect those feelings. I took inspiration from skateboarding and snowboarding games such as *Skate*, *Amped*, and *Tony Hawk's Pro Skater*, taking the general idea of "do tricks to earn points" and combining that with my favorite FPS games like *Halo*, *Call of Duty*, and *Titanfall*. I was reminded of old montages in games like *Call of Duty: Modern Warfare 2* (2009) where players would perform mid-air 360 no scopes with a sniper rifle. 
I wanted to make doing the tricks meaningful, so that the player isn't just performing them for fun (but they can if they want to). 

I decided to make the weapon's power be derived from a meter, which is filled by performing tricks such as jumping, double-jumping, being in the air, and doing a full 360. Each of these tricks will increase the meter until it eventually fills up and the weapon becomes fully powered. If the player does not perform any tricks and the meter is not empty, the weapon's power will gradually decrease.

When the player fires the weapon while it has any amount of charge, the weapon's charge will be reset after that shot has been fired. There is currently no time in between shots.

## Future Improvements
I'm hoping to add various improvements such as:
- More VFX to make the weapon feel more powerful (camera shake, impact particles)
- Improvements to the trick system so that tricks are more satisfying to perform (combo strings, sound effects, better visual feedback)
- More tricks (somersault, wallrunning, dashing, bunnyhopping(?), etc)
- Diverse weapon behavior based on charge (ricocheting off walls, piercing enemies)
