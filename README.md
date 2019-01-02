
# Create SPA: React + Typescript + Parcel

I was about to start yet another personal project, it consists of a SPA (Single Page Application) for a travel journal.

Some time ago a tried [Parcel](https://parceljs.org), I really loved how simple was to create a simple project from scratch using [Typescript](https://www.typescriptlang.org/) + [React](https://reactjs.org) stack. I've decided to create this template project, so next time I want to create a new SPA with my favorite frontend stack, I will only have to clone https://github.com/carlosvin/react-typescript-parcel-template.git.

**You can find a description how I created this project skeleton at: https://carlosvin.github.io/posts/react-typescript-parcel**

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
[Parcel's default optimizations](https://en.parceljs.org/production.html#optimisations) will be applied to generated files.

Files are saved at `dist` folder.
Inside `dist` folder there is also a file with information about bundle content sizes: `dist/report.html`.

# Step by step project creation
You can find this section at: https://carlosvin.github.io/posts/react-typescript-parcel.