# RotaBoard

RotaBoard is a free/libre open source Rota UI developed for [playrota.org](https://playrota.org). It is heavily inspired by Lichess's [Chessground](https://github.com/lichess-org/chessground). It inspires to be a Web/Mobile Typescript UI for the game of Rota.

## Goals

RotaBoard will be designed to fulfill all playrota.org web and mobile apps needs, making it rich in features.

- Well typed with TypeScript
- Fast. Uses a custom DOM diff algorithm to reduce DOM writes to the absolute minimum.
- Small footprint: Goal <10K gzipped (31K unzipped). No dependencies.
- SVG drawing of circles, arrows, and custom user shapes on the board
- Snap to valid moves.
- Entirely configurable and reconfigurable at any time
- Styling with CSS only: board and pieces can be changed by simply switching a class
- Fluid layout: board can be resized at any time
- Support for 3D pieces and boards
- Full mobile support (touchstart, touchmove, touchend)
- Move pieces by click
- Move pieces by drag & drop
  - Minimum distance before drag
  - Centralisation of the piece under the cursor
  - Piece ghost element
  - Drop off revert or trash
- Premove by click or drag
- Drag new pieces onto the board (editor, Crazyhouse) ??
- Animation of pieces: moving and fading away
- Display last move, check, move destinations, and premove destinations (hover effects possible)
- Import and export positions in ROTA notation
  - User callbacks
  - No rota logic inside: can be used for rota variants

## License

RotaBoard is distributed under the **GPL-3.0 license** (or any later version,
at your option).
When you use RotaBoard for your website, your combined work may be
distributed only under the GPL. **You must release your source code** to the
users of your website.

Please read more about GPL for JavaScript on [greendrake.info](https://greendrake.info/publications/js-gpl).
