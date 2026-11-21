# imigraph-pages

Graph imitation pages: the pages of the imigraph project that run in the browser, served as a
web site by GitHub Pages at <https://molntamas.github.io/imigraph-pages/>.

| page | address | what |
| --- | --- | --- |
| [index.html](index.html) | <https://molntamas.github.io/imigraph-pages/> | the list of pages, with a description of each |
| [retro_life.html](retro_life.html) | <https://molntamas.github.io/imigraph-pages/retro_life> | Retro Life, a Game of Life game for phone, tablet and desktop in pixel art with a Japanese touch, in two screens: the map (play, draw, add formations, load maps, zoom), and the same world as a hypergraph on a ring in space (every cell a node: a rock while dead, a light while alive; turn it, tap a node to set its cell); the ordinary rule computes, and the hypergraph is shown as the 17 rules of the page below would hold it |
| [retro_life_v1.html](retro_life_v1.html) | <https://molntamas.github.io/imigraph-pages/retro_life_v1> | v1 of Retro Life: the game as it was on 2026-11-21 (pixel art, six buttons, the ring in space), kept unchanged; `retro_life.html` is always the latest version |
| [game_of_graphs.html](game_of_graphs.html) | <https://molntamas.github.io/imigraph-pages/game_of_graphs> | Conway's Game of Life computed the ordinary way on the left, and the same world as a Wolfram model (a hypergraph and 17 rewriting rules) on the right; a click on a node draws the relations of that cell the way the Wolfram project draws them, step by step; a switch leads to a Game of Life in three dimensions (a box of cells, <https://molntamas.github.io/imigraph-pages/game_of_graphs#3d>) |

The pages are generated in the imigraph repository and copied here; they are not edited here.
`game_of_graphs.html` is the page `life_on_wolfram.html` of the experiment
`wolframs-game-of-life`; `retro_life.html` is the page of the same name of the experiment
`retro-game`, and `retro_life_v1.html` is a kept copy of that page (a version the developer
asked to keep; it is not replaced). `index.html` is written by hand: a new page gets an entry there and a
row in the table above. `.nojekyll` tells GitHub Pages to serve the files as they are.
