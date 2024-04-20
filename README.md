# Discord Activity: Flippy Bird

Explanation:
client/: This directory contains all the code for your game's frontend, built with Phaser 3.
    src/: Houses the core game logic.
        scenes/: Organize different game scenes (preload, menu, gameplay, game over) in separate files.
        game.js: The entry point for your Phaser game, responsible for initialization, scene management, and starting the game.
    index.html: The main HTML file that loads your game's JavaScript and assets.
    style.css: Styles for your game's UI elements.
    package.json: Lists the client-side dependencies, including Phaser 3 and the Embedded App SDK.
    vite.config.js: Configuration for Vite, your build tool.
server/: This directory contains the backend server code built with Colyseus.
    src/: Houses the core server logic.
        rooms/: Contains the Colyseus room logic for your game, handling player connections, state updates, and game logic.
        index.js: The entry point for your server, responsible for starting the Colyseus server and defining game rooms.
    package.json: Lists the server-side dependencies, including Colyseus.
    tsconfig.json: Optional configuration file for TypeScript if you choose to use it.
.env: Stores environment variables, such as your Discord client ID and client secret.
