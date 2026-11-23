# imigraph-pages

Graph imitation pages: the pages of the imigraph project that run in the browser, served as a
web site by GitHub Pages at <https://molntamas.github.io/imigraph-pages/>.

| page | address | what |
| --- | --- | --- |
| [index.html](index.html) | <https://molntamas.github.io/imigraph-pages/> | the list of pages, with a description of each |
| [retro_life.html](retro_life.html) | <https://molntamas.github.io/imigraph-pages/retro_life> | Retro Life, a Game of Life game for phone, tablet and desktop in pixel art with a Japanese touch, in three screens: the map (play, draw, add formations, load maps, zoom; the colour of an alive cell tells how long it has been alive), and the same world as a hypergraph on a ring in space (every cell a node: a faint rock while dead, a light while alive; coloured lines where alive nodes send "alive" to their neighbours; turn it freely, tap a node to set its cell), and one organism (a glider, say) close up, in a steady window on the ring's grid, played slowly, in three views: as it is, as a forecast (who stays, dies and is born, and the number of alive neighbours of every node), and as a directed graph in which every cell is a ring of eight nodes, with four cords across it while the cell is alive (a second model of the same Life, made of arrows between two nodes only); its window zooms from a single cell to the whole world; three looks: the night and the day (the ring in a blue sky, with a sun that goes slowly round it) in pixel art, and one in black and white; full screen, and a way back that first only says it leaves; a tutorial of 16 small lessons, Learn Game of Life, in the settings (the rule, then the buttons and screens of the game, with the button to press blinking, a cheer for every solved lesson, and the arrows going back and forward through the lessons), with a link of its own: <https://molntamas.github.io/imigraph-pages/retro_life#learn>; a book of organisms in the settings (a page for every formation, among them a glider reflector and a glider duplicator), a map with an AND gate built of glider guns, and the name of a known organism on its screen; always the latest version; the ordinary rule computes, and the hypergraph is shown as the 17 rules of the page below would hold it |
| [retro_life_v1.html](retro_life_v1.html) | <https://molntamas.github.io/imigraph-pages/retro_life_v1> | v1 of Retro Life: the game as it was on 2026-11-21 (pixel art, six buttons, the ring in space), kept unchanged; `retro_life.html` is always the latest version |
| [game_of_graphs.html](game_of_graphs.html) | <https://molntamas.github.io/imigraph-pages/game_of_graphs> | Conway's Game of Life computed the ordinary way on the left, and the same world as a Wolfram model (a hypergraph and 17 rewriting rules) on the right; a click on a node draws the relations of that cell the way the Wolfram project draws them, step by step; a switch leads to a Game of Life in three dimensions (a box of cells, <https://molntamas.github.io/imigraph-pages/game_of_graphs#3d>) |

The pages are generated in the imigraph repository and copied here; they are not edited here.
`game_of_graphs.html` is the page `life_on_wolfram.html` of the experiment
`wolframs-game-of-life`; `retro_life.html` is the page of the same name of the experiment
`retro-game`, and `retro_life_v1.html` is a kept copy of that page (a version the developer
asked to keep; it is not replaced). `index.html` is written by hand: a new page gets an entry there and a
row in the table above. `.nojekyll` tells GitHub Pages to serve the files as they are.
