# Vue Webpack SSR Template with server caching

> Vue Webpack SSR Template with server caching

Vue 2.0 + vue-router + vuex, with server-side rendering.

## Features

- Server Side Rendering
  - Vue + vue-router + vuex working together
  - Server-side data pre-fetching
  - Client-side state & DOM hydration
  - Automatically inlines CSS used by rendered components only
  - Preload / prefetch resource hints
  - Route-level code splitting
- Single-file Vue Components
  - Hot-reload in development
  - CSS extraction for production

**A detailed Vue SSR guide can be found [here](https://ssr.vuejs.org).**

## Build Setup Dev Mode

**Requires Node.js 7+**

``` bash
# install dependencies
npm install # or yarn

# serve in dev mode, with hot reload at localhost:8080
npm run dev

# build for production
npm run build

# serve in production mode
npm start
```
