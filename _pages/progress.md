---
permalink: /progress/
title: "Progress"
excerpt: "Stay up to date with the current progression of Erios! An adventure isn't about the destination, it's about the journey you took."
toc: true
toc_sticky: true
header:
    overlay_image: /assets/background3.png
    overlay_filter: 0.5
    image_description: "Looking into the horizon"
    caption: "Looking into the horizon, wondering what to work on next"
---

# Chapters
> Currently Chapter 1: The Hunter is under development. This will be the first playable alpha build of Erios

During the alpha development phase of the game, Erios will be releasing so called "Chapter" updates. Each chapter will focus on a few major features, and once those are implemented, a playable build will be made public for everyone to try out. Whether out of curiousity, to help testing the game or to inspire yourself with new ideas.

# Progression
> Something missing? [Suggest it to be added into the game!]({% link _pages/join.md %}). Erios is a community as much as it is a world, so your feedback matters!

Below you can find a list of planned features, and get a general overview of where the project currently is in terms of development. This list is subject to change. 



## Fundamental
These are the 4 major pillars of content in Erios. For the demo, the campaign will be limited to Hergen. For release, the scope will be the entire region of Weldanar.

- [ ] Campaign (The World of Erios)
    - [x] 1. Save & Load System
    - [ ] 2. Story design for Hergen
    - [ ] 3. Creating the Level of Hergen
    - [ ] 4. Implementing NPCs & Quests into Hergen
    - [ ] 5. Adding side-content
    - [ ] 6. Multiplayer Integration
- [ ] Gamemodes (Alternative ways to play with the games features)
    - [ ] 1. Technical Setup
    - [ ] 2. Gamemode: Waves
    - [ ] 3. Multiplayer Integration
    - [ ] 4. Gamemode: Arena
    - [ ] 5. Gamemode: Horse Racing
- [ ] Dungeons & Raids (Group with other NPCs/Players to face difficult encounters and solve puzzles)
    - [ ] 1. Technical Setup
    - [ ] 2. Dungeon: Mines of Hergen
    - [ ] 3. Multiplayer integration
- [ ] Challenges (Repetitive competitive time-based challenges)
    - [ ] 1. Design

## NPCs
> Characters populate the world and keep it interesting. They may be your foe or ally, yet there is a lot you can do with them. They will also do things on their own, as Erios is the world that they live in.

Some items in the list may have a tag like `[C1]`, this means that this functionality was added / is going to be added in that chapter update

- [x] State System
- [ ] Navigation System
    - [x] `[C1]` NavMesh Phase 1: Basic Terrain
    - [ ] NavMesh Phase 2: Avoidance System
    - [ ] NavMesh Phase 3: Advanced Terrain ()
- [ ] Task System
- [ ] Follower System
- [ ] Quest System
- [ ] Speech Sounds
    - [x] Speech Sounds Phase 1: Characters make random sounds when speaking
    - [ ] Speech Sounds Phase 2: Changing speed, pitch & tone
- [ ] Equipment System
    - [x] Equipment System Phase 1: Functionality
    - [ ] Equipment System Phase 2: User Interface
- [ ] Faction/Reputation System
- [ ] Character Customization Interface (for the player)
- [ ] Trading & Economy System

### Creatures
> The world is large, and even in a region like Weldanar, the ecosystem is diverse

- [ ] Deer
- [ ] Birds
- [ ] Wolves

## World
> The world within Erios is a living world on itself. Things happen, whether the player is there are not.

- [ ] Time System
    - [x] Time System Phase 1: Functionality
    - [ ] Time System Phase 2: Visualization (i.e. the time of day changing from day to night)
- [ ] Weather System
- [ ] Ecosystem
    - [x] `[C1]` Ecosystem Phase 1: Basic implementation
    - [ ] Ecosystem Phase 2: Evolution
    - [ ] Ecosystem Phase 3: Visual change
- [ ] Dynamic Events
- [ ] Interactables System
- [x] Loading Screen
- [ ] Transportation
    - [ ] Horse
    - [ ] Wagon
    - [ ] Ship

## Multiplayer
> Erios can be played as a full singleplayer game, yet it can also be played as a full multiplayer game. So play with your friends!

- [x] Lobby Server
- [x] Chat System
    - [x] Chat Commands
- [ ] Player List
- [ ] Reconnect System
- [ ] Favorite server list

## Items & Tools
- [ ] Weapons
    - [ ] Sword
    - [ ] Bow
    - [ ] Spear
    - [ ] Unarmed
    - [ ] Shield
- [ ] Tools
    - [ ] Torch
    - [ ] Grappling Hook

## Skills
> Erios features various skills that players can progress towards

- [ ] Archeology
- [ ] Arist
- [ ] Blacksmithing
- [ ] Builder
- [ ] Carpentry
- [ ] Cooking
- [ ] Explorer
- [ ] Farming
- [ ] Fishing
- [ ] Forestry
- [ ] Guard
- [ ] Herbalism
- [x] `[C1]` {% glossary Skill_Hunting, display: Hunting %}
- [ ] Jewel crafting
- [ ] Leatherworking
- [ ] Mining
- [ ] Thieving

## Accessibility
> Erios is a world for everyone. So there are lots of settings to make the game more accessible and customizable

- [x] Audio Settings
- [x] Graphic Settings
- [x] System Settings 
- [ ] Rebind Settings
    - [x] 1. Changing Rebinds
    - [x] 2. Saving & Loading
    - [ ] 3. Advanced Rebind modifiers (Double press, hold) 
- [ ] UI Settings
    - [ ] Changing fonts
    - [ ] Changing HUD positioning
    - [x] `[C1]` Dynamic UI scaling
    - [x] `[C1]` Change UI scale for better readability
    - [x] `[C1]` Aspect Ratio
- [ ] Localization
    - [x] English
    - [x] Dutch
    - [ ] Japanese (WIP)
- [ ] Operation Systems
    - [x] Windows
    - [ ] Linux
    - [ ] Mac

## Collectables
> Collect everything!

- [ ] Completion % tracker
- [ ] Achievements
- [ ] Cards
    - [x] Cards Phase 1: Design
    - [ ] Cards Phase 2: Collecting cards throughout the world
    - [ ] Cards Phase 3: Collection UI

## Moddability
> For players to be able to extend upon the world of Erios is an important feature

- [ ] Mod Loader
    - [x] Mod Loader Phase 1: Ability to load mods
    - [ ] Mod Loader Phase 2: Creating & managing mod packs
- [ ] Custom Models
- [ ] Custom Audio Files
- [ ] Custom Levels
- [ ] Custom Scripts
- [ ] Custom Entities (Characters / Creatures)

## Replayability

- [ ] New Game+
- [ ] Randomizer

## Tools
> In-game tools are valuable for mod developers. Thus Erios will offer them

- [ ] Console Commands
- [ ] Level Editor
    - [x] Manip (Position, Rotation, Tool)
    - [x] Local positioning
    - [ ] Creating & Loading custom prefabs
- [ ] Character Editor
- [ ] Quest Editor

## Technology
> Interesting technologies which makes Erios more unique

- [x] Dynamic Recoloring (Recolor any object at runtime)
- [x] Low Polifier Tool (Convert any object into Erios its low poly art style)
- [x] LUA Documentation Generator (LUA Binding + Website)

## Post-Release
> A list of confirmed ideas, but these will only be implemented post-release