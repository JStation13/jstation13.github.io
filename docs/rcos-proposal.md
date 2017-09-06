# JStation13

JStation13 (JS13) is a remake of the classic BYOND game Space Station 13 (SS13). The purpose of this remake is to rewrite SS13 in a more common (and better) programming language, as well as making it more accessible to more users.

## Milestones

### ① Basic Thin Client
Before delving into the server, a very basic representation of the client should be developed as it will help aid in development of the server (since it will be easier to understand some of the complex server-side systems).

Tasks:
* WebGL Renderer
* WebSocket Networking
* Simple Assets

### ② Basic Server
The game is tile-based, so the server must at the very least support that functionality. It must also support networking with the client. Finally, having basic entities that can interact with the tile system should be implemented.

Tasks:
* WebSocket Networking
* Tile System
* Simple Player Entities

### ③Atmospherics
Space Station 13 started life as an atmospheric simulation. Therefore, an early core system that should be implemented is atmospherics. The atmospherics in this remake will be either tile or subtile based.

Tasks:
* Research Atmospheric Equations
* Tile / Subtile Atmospheric Implementation