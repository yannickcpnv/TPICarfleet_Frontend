# CarFleet front end v0.2.0

This is the front-end application of CarFleet.

### Prerequisites

- Nodejs with npm -> https://nodejs.org/en/download
- Yarn globally -> `npm install --global yarn`

## Installation

Run `yarn install`.

## Push in a production server

Once you have access to your server, do this tasks in this order :

1. Install the prerequisites
1. Run yarn install.
1. Run yarn build.
1. Move manually the dist folder your server.

## Build

Run `yarn build` to build the project to production. The build artifacts will be stored in the `dist/` directory.
flag for a production build.

## Usage

Simply run application and navigate with the browser.

Usage videos :

### Companies

- [Companies](https://youtu.be/Uj-ytaJhz1I)
- [Company detail](https://youtu.be/YVXg963OmCQ)

### Users

- [Users coming soon...](https://youtu.be/ceh57pPFyTw)
- [Create a new user coming soon...](https://youtu.be/UiAH7_0JF0Q)
- [Edit an user coming soon...](https://youtu.be/efMSJDp7acA)

## Documentation

Run yarn generate:doc to generate API documentation in the folder documentation.

The command yarn generate:doc:serve starts a server at the port 51001 and open the doc in the default browser after the generation is complete.

The doc will not be committed with git.

## Development server

Run `yarn start:dev` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you
change any of the source files.

Navigate to `http://localhost:4200/`.

### Production server

Run `yarn start` for a production server.

Navigate to `http://localhost:4200/`.

## Tests

_There is only basic tests of the front-end application._

### Unit tests

Run `yarn test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### End-to-end tests

Run `yarn e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Fix vulnerabilities dependencies

Use the command `yarn-audit-fix` to fix the vulnerabilities of dependencies.

If it doesn't work, please refer to this [link](https://stackoverflow.com/a/60878037) and fix the rest manually if 
necessary.
