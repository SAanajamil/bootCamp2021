# bootCamp2021

Essential Typescript4

Step 1: Install Node.js(https://nodejs.org/en/download/) LTS.

Step 2: npm install --global typescript@4.2.2(write the code in terminal and run)

Step 3: Install a Programmer’s Editor (https://code.visualstudio.com)

Initializing the Project Folder Package.Json run this command (npm init --yes)

Creating the Compiler Configuration File tsconfig.json.write mentioned below code in this file.

{
 "compilerOptions": {
 "target": "es2018",
 "outDir": "./dist",
 "rootDir": "./src",
 "module": "commonjs"
 }
}
Adding a TypeScript Code File index.ts in src file.

Compiling the Code by "tsc"

Executing the Compiled Code by node ./dist/index.js.

