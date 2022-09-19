# Self Replicating HTML

Each `.html` file in this repository contains a self replicating program (a kind of [Quine](https://en.wikipedia.org/wiki/Quine_%28computing%29)). When a file is opened in a browser, it displays its source code then modifies it, replacing itself with the modified version in a recursive loop.

Each iteration or "frame" is a self contained program, with the property that if you copy the visible text into a new `.html` file while it's running and open it, the new file will continue from the point you copied it from.

The files in this repository are currently starting points aimed at exploring the various possibilities this form offers.

## Try it live

**[`axiom.html`](asdasd)**

Proof of concept showing the mechanism for rendering a Quine and modifying and replacing itself with the modified version.

**[`ouroboros.html`](asdasd)**

A game of snake that renders each iteration as a frame, using the source code as an interactive interface.

**[`transmission.html`](asdasd)**

Each instance passes a hash of itself to its progeny, making it increasingly expensive to find the source code of the progenitor.
