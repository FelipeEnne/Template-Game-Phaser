# Template Game (Phaser)

Template to start creating a game using Phaser 3, based on [Phaser 3 Webpack Project Template](https://phasertutorials.com/creating-a-phaser-3-template-part-1/) and [A Modern Web Development Setup For Phaser 3](https://snowbillr.github.io/blog/2018-04-09-a-modern-web-development-setup-for-phaser-3/).

Built with **Phaser 3**, **Webpack 5**, and **Babel 7**.

### Requirements

[Node.js](https://nodejs.org) **22.15.0 or later** is required to install dependencies and run scripts via `npm`.

### Installation

```bash
npm install
```

Place game assets under an `assets/` folder at the project root (for example `assets/logo.png`). The build copies that folder into `dist/assets/`.

### Available Commands

| Command | Description |
| --- | --- |
| `npm start` | Start the development server with hot reload (http://localhost:8080) |
| `npm run build` | Build the production bundle into `dist/` |
| `npm run watch` | Rebuild automatically when source files change |
| `npm run server` | Serve the production build from `dist/` (http://localhost:3000) |
| `npm run lint` | Run ESLint on `src/` and apply fixes |

### Getting started

```bash
npm install
npm start
```

To serve a production build:

```bash
npm run build
npm run server
```

### Scenes

* **Boot** – the first scene loaded by Phaser; loads assets required by the preloader scene.
* **Preloader** – displays a logo and progress bar, and loads all assets needed in the game.
* **Title** – title screen with buttons to start the game, view credits, and open options.
* **Options** – settings players can change (for example mute audio).
* **Credits** – credits for your game.
* **Game** – main game logic.

### Credits

Logo image – Image by IO-Images from Pixabay
