### Examples of type-checked p5.js code

These won't be examples of best practices - they're mine, and I'm no expert, and I often start with student code and enhance it to demonstrate possibilities, generally avoiding advanced techniques even if I know them. 

Here I'll point to a few p5.js project done with type-checking

### Type-checked *JavaScript* examples

* ["lunar lander" game](https://github.com/nbogie/lunar-lander-p5js) p5.js v2 global-mode with  type-checked JavaScript.  No bundler.
*   It is playable [here at openprocessing](https://openprocessing.org/sketch/2711492) however the code is easier to read in the repo as it's split by file.

### TypeScript examples
* [Split (quad bisect painting)](https://github.com/nbogie/split-wccc-20251119-p5-ts-global) for WCCChallenge - p5.js v2 global-mode with TypeScript (on vite).  Includes single-file readable bundling to publish ~readable code back on p5-web-editor or openprocessing, etc.
* [Space Scroller](https://github.com/nbogie/p5js-space-scroller) an old (2019) self-playing game I ported to TypeScript.  p5.js v1 global-mode with TypeScript (uses bundle-sync, and tsc builds to a single file)
*   - It is "playable" [here on gh pages](https://nbogie.github.io/p5js-space-scroller/), in as much as any of my "games" are playable.
