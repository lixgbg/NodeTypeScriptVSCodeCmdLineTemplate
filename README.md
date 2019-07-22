# NodeTypeScriptVSCodeCmdLineTemplate
A template project for setting up Node.js, TypeScript and Visual Studio Code for a CMD line application.

Inspired by articles <https://itnext.io/how-to-create-your-own-typescript-cli-with-node-js-1faf7095ef89> and <https://code.visualstudio.com/docs/typescript/typescript-tutorial>


- npm run build — Compile TypeScript index.ts file in src folder to index.js and index.d.ts in lib folder
- npm run test — Run program
- npm run create — Runs build and test scripts together
- npm start — Starts program and listens for changes, and reloads as necessary
- npm run refresh — Deletes the node modules, package-lock.json and runs npm install for a complete refresh
- npm run installbin — Installs the CLI program globally using sudo npm i -g and launches it

<b>TODO</b>: Add cmd line arguments to the <code>npm start</code> and <code>npm run test</code> commands, as well as VisualStudio Code launch.json configuration.
