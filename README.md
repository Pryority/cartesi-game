# Cartesi TypeScript DApp Template

## ⚠️ Setup

1. Had to use find the correct version of the sdk on GitHub because docs point to 0.6 but minimum required is 0.9, which Docker tells you after you wait a long time to build (and ultimately fail) the default repo's build.

2. I had to change the default rollup server port from 5004 to something else, like 8080 -- `cartesi run --listen-port 8080`.

3. `cartesi run` needs to be `cartesi run -v --listen-port 8080` to see progress of docker container pulling.

4. Had to manually start **anvil**.
