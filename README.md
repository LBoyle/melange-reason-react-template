# melange-reason-react-template

A simple project using melange.re, ReasonML with the latest React.js

## Getting started

### npm

You may use npm or yarn as normal

### esy

You will need [esy](https://esy.sh) package manager to obtain OCaml and Melange sources. See `esy` installation instructions [here](https://esy.sh/docs/en/getting-started.html#install-esy).

Install dependancies

```bash
npm i
esy
```

You will need two terminals

```bash
npm run re:watch
npm run parcel
```

Navigate to `localhost:1234`

### Production

Output is in `dist/`

```bash
npm run parcel-build
```

## Complications

I have not used the watchers built into dune, instead I use chokidar-cli to watch .re files and trigger the recompile
