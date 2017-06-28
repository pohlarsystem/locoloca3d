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

- Game controls should follow common patterns.

- Worlds must be serializable and deserializable (save/load game).


## Available [game engines](https://github.com/showcases/game-engines)

*Incomplete list:*

- Unity 3D

- Unreal

- Babylon JS
