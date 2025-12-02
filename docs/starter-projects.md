# (my) starter / template projects for p5.js

This is a list mostly for myself, of my old and new p5 starter projects, some of which are under construction.

Almost all of these incorporate *type-checking* and *intelli-sense* for your code.  
* With type-checking you get much more help finding bugs quickly.  
* With intelli-sense you get auto-completion of p5 function and variable names as well as inline documentation for those.  
* Any project that includes "type-checking" in its title also includes this intelli-sense.

## JavaScript Projects

### JavaScript: with type-checking

-   ⭐️ NEW 1️⃣: p5 v1 🌍 global-mode *JavaScript* starter with type-checking (2025): https://github.com/nbogie/p5-v1-js-typechecked-global-mode-starter
    -   intended for vscode
    -   type-checking, intelli-sense, explanation of files
    -   `npx degit nbogie/p5-v1-js-typechecked-global-mode-starter my-awesome-p5-project`
    -   requires node.js be installed, for vscode to acquire the p5 types automatically.

-   ⭐️ NEW 1️⃣: p5 v1 🌍 global-mode *JavaScript* starter with type-checking (alternative using npm) (2025): https://github.com/nbogie/p5-v1-js-typechecked-global-mode-local-types-starter
    -   intended for vscode
    -   type-checking, intelli-sense, explanation of files
    -   `npx degit nbogie/p5-v1-js-typechecked-global-mode-local-types-starter my-awesome-p5-project`
    -   requires node.js be installed and simple use of `npm install` on the command-line to install the p5 types.

-   ⭐️ NEW 2️⃣: p5 v2 🌍 global-mode *JavaScript* starter with type-checking **no-node-needed** (2025): https://github.com/nbogie/p5-v2-js-typechecked-global-mode-starter
    -   intended for vscode
    -   type-checking, intelli-sense
    -   no node.js or command-line required
    -   not ideal: includes the (big) types files in the repo and requires they be updated manually on p5 version update.
    -   `npx degit nbogie/p5-v2-js-typechecked-global-mode-starter my-awesome-p5-project`
    -   could be improved by having up-to-date p5 types in definitely-typed for the remote type-aquisition mechanism.  See [publish to @types](https://www.typescriptlang.org/docs/handbook/declaration-files/publishing.html#publish-to-types) in the typescript docs.

-   ⭐️ NEW 2️⃣: p5 v2 🌍 global-mode *JavaScript* starter with type-checking - **node-required** (2025): https://github.com/nbogie/p5-v2-js-typechecked-global-mode-with-node-starter
    -   intended for vscode
    -   type-checking, intelli-sense
    -   not ideal: requires node.js for downloading p5 - for the types, only
    -   would be rendered unnecessary by having up-to-date p5 types in definitely-typed for the remote type-aquisition mechanism with its sibling starter.
    -   `npx degit nbogie/p5-v2-js-typechecked-global-mode-with-node-starter my-awesome-p5-project`

-   OLD 1️⃣: p5 v1 🌍 global-mode *JavaScript* starter w type-checking (2023): https://github.com/WeAreAcademy/p5js-js-global-mode-starter
    -   type-checking and intelli-sense
    -   no node, no bundler, suggests live server but whatever.


### JavaScript: sketch-as-ESM

-   ⭐️ NEW 1️⃣: sketch-as-ESM p5 v1 🌍 global-mode ESM commented example at openprocessing: https://openprocessing.org/sketch/2784559
-   ⭐️ NEW 1️⃣: sketch-as-ESM p5 v1 🌍 global-mode ESM commented starter project https://github.com/nbogie/p5-v2-esm-js-typechecked-global-mode-starter

## TypeScript Projects

-   ⭐️ NEW 2️⃣: p5 v2 ts 🌍 global-mode, vite-based, 2025: https://github.com/nbogie/p5-v2-ts-global-mode-starter
    -   vite
    -   intended for degit but optional: `npx degit nbogie/p5-v2-ts-global-mode-starter`
-   OLD 1️⃣: ts 🌍 global-mode starter for p5 v1: https://github.com/WeAreAcademy/academy-p5js-ts-global-mode-starter
    -   uses browser-sync, modified from https://github.com/Gaweph/p5-typescript-starter
-   OLD 1️⃣: ts instance-mode starter 2023: https://github.com/nbogie/p5-ts-starter-23
    -   uses parcel 2 bundler


## Related

-   OLD: TS + React w the kitchen sink (though no P5): https://github.com/WeAreAcademy/academy-react-ts-starter-vite
    -   (no p5.js in this one)
    -   uses vite
    -   prettier
    -   eslint
    -   vitest unit testing
    -   vscode tasks, github workflows
    -   etc
    -   
-   OLD: threejs starter / examples
    -   https://github.com/nbogie/threejs-ts-starter
        -   parcel 1 based
        
## credits

I think in each individual project I've credited any sources used. However big shout out to this [p5 ts starter](https://github.com/Gaweph/p5-typescript-starter) by Gareth Williams (Gaweph) which I think the typescript setups for all my p5 v1.x starters have been based on.
