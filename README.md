# Purpose

Simple hello-world app from the Gatsby docs

## Development

```sh
npm install -g gatsby-cli
gatsby develop
```

This will start a server @ localhost:8000

## Deployment

Ensure ./gatsby-config.js has the proper prefix for you if deploying
to gh-pages

```sh
npm run deploy
```

The above is equivalent to:

```sh
gatsby build --prefix-paths && gh-pages -d public/
```
