# Teaching Platform Frontend

React and Vite frontend for the Teaching Platform.

## Run locally

```sh
npm ci
npm run dev
```

The Vite development server proxies `/api` to the backend on port `3001` by
default. Set `API_PORT` in your local environment if the backend uses another
port.

## Build and deploy

```sh
npm run build
```

Deploy this repository as a Vercel project with the framework preset set to
Vite, build command `npm run build`, and output directory `dist`. The included
`vercel.json` rewrites API requests to the existing Render service at
`paragon-academy.onrender.com`. If the backend is deployed to a different
service, update that API rewrite destination before deploying the frontend.
