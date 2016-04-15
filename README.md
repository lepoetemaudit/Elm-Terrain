# Elm Terrain
A proof-of-concept terrain renderer using Elm WebGL

# Demo

See http://lepoetemaudit.github.io/elm-terrain

# Running locally

Clone the repository and run `make` followed by `make serve`, then navigate to http://localhost:4079/terrain.html

Uses a slightly modified version of https://github.com/elm-community/elm-webgl found in `./libs`, mainly to allow setting
`glClearColor` and to correctly set desired texture properties (such as mipmap filters)

# Credits

Textures are from http://spiralgraphics.biz/packs/terrain_lush/

The heightmap is from http://terrain.party and is of Derwentwater in the Lake District, England, with some fiddling and smoothing in Gimp.