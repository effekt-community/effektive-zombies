> [!NOTE]
> This is a community-maintained fork of a MIT-licensed student project in the *Effective Programming with Effects* course in winter semester 2024/2025.
> Be warned that this is not an officially endorsed project, the code in this repository may be not idiomatic Effekt.
> 
> The original repository is https://github.com/martin-ilgner/effektive-zombies

## Effektive Zombies

This is a top-down survival game written in Effekt.

## How to Play

Install Effekt: https://effekt-lang.org/docs#installing-effekt

Run with Effekt: `effekt ./src/main.effekt --backend js-web --includes .`

Open `out/main.html`

## Controls

WASD to move, mouse for aiming, left-click to shoot.

## Gameplay Mechanics

`Wave`: Shown in the top left corner of the in-game screen. The higher the wave, the more frequent zombies spawn.

`Combo`: Shown in the bottom right of the in-game screen. The higher your combo, the more points you get for each zombie killed. Your combo increases for every zombie you kill. It gets reset if you either get hit by a zombie or you miss a bullet (bullet leaves the screen and thus cannot hit zombies anymore).

\
\
\
\
\
\
Template: https://github.com/jiribenes/effekt-template
