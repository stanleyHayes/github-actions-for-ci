# github-actions-for-ci

Learn how to use GitHub Actions!. github actions for ci is an application containing JavaScript, HTML, CSS. The repository layout and entry points below describe the checked-in implementation.

## Repository layout

- `public/` — 1 tracked file(s).
- `src/` — 3 tracked file(s); source examples: `src/game.js`, `src/index.js`.

## Local setup

Run each package setup block from the repository root. For workspace repositories, install dependencies at the root before running application-specific scripts.

Clone this repository and enter its directory:

```sh
git clone https://github.com/stanleyHayes/github-actions-for-ci.git
cd github-actions-for-ci
```

### Node package: `package.json`

Use Node.js and npm.

```sh
npm install
```

- `npm run dev` — runs the declared `dev` script (`npx webpack --config ./src/webpack.config.js --mode development --watch`).
- `npm run build` — runs the declared `build` script (`npx webpack --config ./src/webpack.config.js --mode production`).
- `npm run test` — runs the declared `test` script (`npx standard && npx jest`).

## Source entry points

- [babel.config.js](babel.config.js)
- [index.html](index.html)
- [src/game.js](src/game.js)
- [src/index.js](src/index.js)
- [src/webpack.config.js](src/webpack.config.js)

## Development notes

Commands above come from the tracked manifests and source layout. External services and runtime configuration may be required. Documentation updates do not establish that the application is deployed or that its tests pass.

## Previous project notes

# Tic Tac Toe Game

Learn GitHub Actions through a fun little game.
