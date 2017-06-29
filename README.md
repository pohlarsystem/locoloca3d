# Loco Loca 3D

*This document is a design document for Loco Loca 3D, to aid development and to document the project's goals and wanted features.*

This is a design document.
It does not describe a current, nor targeted state.
Open statements to be discussed are written using *may*, *must*, and *should* etc.


## Task list

- [ ] Write rough outline of the game's concept
- [ ] Write list of basic features
- [ ] Collect game engines to chose from (including their pros and cons)
- [ ] Select game engine to work with
- [ ] Bootstrap the game
- [ ] Implement navigational features and controls
- [ ] Implement abstract features for city building
- [ ] Find 3D artist(s) to create assets


## Game concept

*Loco Loca 3D* (working title) may become a sandbox world simulator.
It may draw inspiration from games like LEGO Loco, Sim City and similar games.
The game's mechanics rely on the game elements and their reaction to other elements.
For example, building houses would bring citizens to the world, which then may want to walk to certain places of their interest, which may involve using public transportation.

While the game may be a sandbox game, so that resources never matter, a city (or world) may be ranked using an overall "health" score.
If a less sandbox-ish approach is wanted, collection of resources (construction and/or consumption) may also be a mechanic that could be introduced.


## Game features

- Game controls should follow common game design patterns.

- Worlds must be serializable and deserializable (save/load game).

- The game should run on all major platforms.

- Picking up the game should be as barrier-free as possible (easy to get, easy to install, easy to launch).

- The game will most likely use 3D tile sets, so a coordinate grid can be relied on.


## Development roadmap


### Stage 0

- Build a prototype with a floor and basic navigation.

- Compile it for all major platforms and verify it works.

- Implement basic construction of simple, inanimate objects.

- Implement world loading/saving.


### Stage 1

- Implement railroad construction.

- Implement animated trains.


## Available [game engines](https://github.com/showcases/game-engines) *(incomplete list)*

- Unity 3D

  - **Pro**: Exports to multiple platforms
  - **Pro**: Has a large community and huge ecosystem full of support and assets
  
- Unreal

  - **Pro**: Exports to multiple platforms

- Babylon JS


## Game elements *(incomplete list)*

This is a basic list of planned game elements and how they work.


### Citizens

- Citizens have a home and cannot exist in the world without home.

- Citizens will do something.

- When they finished the task they descided on doing, citizens will decide what to do next.

- Their decision must only consider options in the world, e.g. they must not decide to walk to a park when there is none.
