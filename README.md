WIP
---

This project is a *work in progress*. The implementation is *incomplete* and
subject to change. The documentation can be inaccurate.

pgg
===

The goal of this project is to provide insight and facilitate the understanding
of how to create a pretty good game (pgg).

Documentation
-------------

Documentation provided by GoDoc.

   - gl
      - [tileset][gl/tileset]: handles collections of one or more tile images using OpenGL.
   - [grid][]: divides the game world into a series of contiguous grid cells.
   - [tileset][]: handles collections of one or more tile images.
   - [view][]: supervises the visible portion of the screen.

[gl/tileset]: http://godoc.org/github.com/mewmew/pgg/gl/tileset
[grid]: http://godoc.org/github.com/mewmew/pgg/grid
[tileset]: http://godoc.org/github.com/mewmew/pgg/tileset
[view]: http://godoc.org/github.com/mewmew/pgg/view

Command documentation
---------------------

Command documentation provided by GoDoc.

   - cmd
      - [tiledump][cmd/tiledump]: extracts tile images contained within tile sets.
      - [world][cmd/world]: initializes and renders a simple game world.
   - gl
      - cmd
         - [globe][gl/cmd/globe]: initializes and renders a simple game world using OpenGL.

[cmd/tiledump]: http://godoc.org/github.com/mewmew/pgg/cmd/tiledump
[cmd/world]: http://godoc.org/github.com/mewmew/pgg/cmd/world
[gl/cmd/globe]: http://godoc.org/github.com/mewmew/pgg/gl/cmd/globe

public domain
-------------

This code is hereby released into the *[public domain][]*.

[public domain]: https://creativecommons.org/publicdomain/zero/1.0/
