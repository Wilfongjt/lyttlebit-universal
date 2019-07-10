# lyttlebit-web

> LyttleBit

# Features
* Provides support for environment Variables
* Acts as a placeholder for domain
* Provides a entry point for LyttleBit


## Build Setup

``` bash
# install dependencies
$ npm run install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).


## Docker-Compose
### DEV Build Container
Build when you first download the repo.
Build when or if you change the docker-compose.yml
Build when or if you change the Dockerfile
```
cd lyttlebit/
docker-compose build
```

### DEV Start Container
```
cd lyttlebit/
docker-compose up
```

## DEV Website
Use Chrome or Firefox
* http://localhost:3000


## Common Issues
* Safari
  * DONT USE SAFARI it has issues with AWS Gateway
  * Preflight response is not successful
  * XMLHttpRequest cannot load ... due to access control checks
  * Failed to load resource: Preflight response is not successful
