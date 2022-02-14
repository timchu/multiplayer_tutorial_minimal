 We are using this tutorial: https://gamedevacademy.org/create-a-basic-multiplayer-game-in-phaser-3-with-socket-io-part-1/  to create a simple multiplayer game with trivial movement functionality using arrow keys.

Requires an NPM and node installation.

Run (to install npm packages):

> npm i

> npm i express

> npm i http

> npm i jsdom

> npm i socket.io

> npm i datauri

Then to start server:

Run:

> node server.js

Access the simple game by opening ``localhost:8081'' on the web browser. Open two windows to test
multiplayer functionality, and use the arrow
keys to move ships around.

Small modifications were made in the server.js file compared to the
tutorial, because the tutorial does not work out-of-the-box anymore.

