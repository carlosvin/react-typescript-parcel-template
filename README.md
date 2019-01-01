# Create SPA: React + Typescript + Parcel

I was about to start yet another personal project, it consists of a SPA (Single Page Application) for a travel journal.

Some time ago a tried Parcel, I really loved its simplicity for starting a simple project from scratch using Typescript + React stack, so I've decided to create this template project, so next time I want to start a new SPA with my favorite frontend stack, I will only have to clone https://github.com/carlosvin/react-typescript-parcel-template.git.

# Quick start

## Development server

```bash
git clone https://github.com/carlosvin/react-typescript-parcel-template.git
cd react-typescript-parcel-template
yarn install
yarn start
```
Last `yarn start` command will:
- start a development server at http://localhost:1234 with [hot module replacement](https://en.parceljs.org/hmr.html)
- build automatically development javascript files with source maps

Basically each time you save a file, you will see automatically the result at http://localhost:1234 without refreshing the page.

## Build production bundle

```bash
yarn build
```
It will apply [Parcel's default optimisations](https://en.parceljs.org/production.html#optimisations).

Files are generated at `dist` folder.