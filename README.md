# Next.js starter

An example site which uses [Next.js](https://nextjs.org/) as a complete build system.

The following Next.js features are demonstrated:

* basic page creation
* dynamic routes generated from markdown posts
* article indexes
* static generation (render at build time)
* server-side rendering (render at request time)
* client-side hydration
* custom React components
* development and build processes such as hot reloading


## Installation

Ensure Node.js v10 or above is installed, clone the repository, and install all modules:

```sh
git clone git@github.com:sitepoint-editors/nextjs-starter.git
cd nextjs-starter
npm i
```


## Development mode build

Launch the Next.js build server:

```sh
npm run dev
```

(or `npx next dev`)

Navigate to <http://localhost:3000> in your browser.


## Production mode build

Run the Next.js build process:

```sh
npm run build
```

(or `npx next build`)

Then test with `npm run start` or `npx next start`.

The files generated in the `.next` folder can be uploaded to any web host with Node.js support.
