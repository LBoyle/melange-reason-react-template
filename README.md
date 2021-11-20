# melange-reason-react-template

A template project using melange.re, ReasonML with the latest React.js

## Getting started

### npm

You may use npm or yarn as normal

### esy

You will need [esy](https://esy.sh) package manager to obtain OCaml and Melange sources. See `esy` installation instructions [here](https://esy.sh/docs/en/getting-started.html#install-esy).

Install dependancies

```bash
npm i
```

```bash
esy
```

You will need two terminals

```bash
npm run re:watch
```

```bash
npm run parcel
```

Navigate to `localhost:1234`

### Production

Output is in `dist/`

```bash
npm run parcel-build
```

## Notes

I have not used the watchers built into dune, instead I use chokidar-cli to watch .re files and trigger the recompile

I have included `@opam/ocaml-lsp-server` for editor support, I use [OCaml Platform VSCode](https://marketplace.visualstudio.com/items?itemName=ocamllabs.ocaml-platform)
