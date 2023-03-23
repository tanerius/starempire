# Star Empire

A small game made to demonstrate an evolving AI. The objective is to destroy all other players on the map and be the last man standing.

## How the game works

This game is based of a very old linux game called Qonk with a lot of additions to it. But basically each player must sieze control of as many planets as possible by sending ships there.  
  
The setting of the game is a solar system of planets. Your goal is to conquer all of the planets in the game by sending ships there. Planets that are under your control generate new ships. Simple AI players are playing against you. The AI evolves its strategy.  
  
Planets can be in any of the three states:

- A planet/moon can be occupied by a player (AI or Human)
- A planet/moon can be owned by you
- A planet/moon can be unoccupied

Occupied planets generate armies (ships) at a rate determined by research, planet type, moon presence.

Ships have the following attributes based on research:

- Speed
- Damage