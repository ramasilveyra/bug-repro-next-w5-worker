# Bug repro of next.js issue with webpack 5 and worker-loader

When using next.js with webpack 5 and worker-loader an exception appears.

1. `yarn`
1. `yarn dev`
1. Open dev tools console.
1. Desired behaviour: expect to see log from web worker (`message from web worker: Bye!`).
1. Current behaviour: exception from ReactRefresh (`Uncaught TypeError: Cannot read property 'push' of undefined`).
