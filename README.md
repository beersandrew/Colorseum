# Group Project Overview

# Tasks

## Must Have
1. Gun system
   - Pressing shoot fires one laser
   - no travel time on shooting
2. Local Multiplayer
3. Dashing mechanic
4. Basic UI (Main Menu, Death / Win screens)

## Should Have
1. Neon enviroment / aesthetic + Styling of Menus
2. 1 minute timer to escape the tower (UI elements + blueprints for death after 1 min)
3. Round system (best of 1/3/5/7?) (Includes UI components)
4. Speed Powerup (increase max walk speed)
5. Laser overheat
6. Sound (background music, gun animation sound, death sound, steps, swing sound, dash sound, power up sound, main menu background music, button press sound)
7. Health powerup (health blocks, start with 1 and up to 3(max) 

## Want to Have
1. Ricochet'ing lasers
2. Gun Strength Powerup
3. Laser ammo
4. Another level

## Won't Have
1. Online multiplayer
2. Gravity based bullets
3. Different Guns

# Feel of the game
- Different experience each time
- Fast paced, focused on movement controls
- Neon aesthetic, bright lights
- Pickups
- How long is a round? (1 min (maximum!) in the tower, 1-3 min of battle) (at least 15 seconds in the tower)
- What does the winner of the race to the center get? positional advantage of being able to wait for the other player to leave the tower
- Start of the round: big banner with on theme UI
- Death: Big banner on theme with UI -> player shatters or dies in some epic way
- No entering someone else's tower
- Multiple doors to exit / forcefield to protect the slower player from getting camped
- Health of the player is associated with the color of the his outfit (red-1, yellow-2, green-3...or others?)
- Change sensitivity of controllers in the menu
- Platforms break during the game so the player can't camp, platforms break for the entire round?
- Platforms could glow when players land
- UI: Timer for the tower, Rounds system for who is leading

# Normal playthrough
1. Start Game
2. Main Menu -> select number of players
3. Start on Tower -> towers are same
4. Swing through the tower
5. Race through the breakable floors
6. Find powerups throughout the tower
7. Make sure to exit the tower within a minute
8. Find your spot to wait / hunt the other player
9. Gameplay is mostly in the air
10. Shoot and win!

# Project Structure

## Assets
Meant for images & sounds, create a folder to describe where the asset is being used here

## Blueprints
Meant for all of our logic

### Mechanics
For all of our different main components / mechanics

#### Breakable Floors
For all breakable floor logic and variations

#### Swinging
For all swinging related actors

Note: some logic is in the player character for now and that's fine for now

## Characters
Meant for all character models / animations, only the default Unreal one for now

## Level Prototyping
This is a bad name for this folder, it has all the floor assets / meshes used from the default Unreal Projects, we can use them for prototyping the levels

## Maps
For all of our maps


# [Current Issues](https://github.com/FGGameEngines/FG22GE-ST/issues)


## Links
1. [Game Design Document](Documentation/GameDesignDocument.md)
2. [Team Contract / How to Work](Documentation/TeamContract.md)
3. [Project Description](Documentation/ProjectDescription.md)
4. [Miro Board for Game Ideas](https://miro.com/welcomeonboard/WHZKMFc5VjU3RmpJcFN3djVqQVhMWnpjTFF0anhqaGtkSENnVkloMWdnTEt1SUxwOEcxRjFaZzNtQzQ5SEI1V3wzNDU4NzY0NTI2NjcyNTA5NzU3?share_link_id=524689652178)
