# type-starter

## A TypeScript starter template

### *Type-starter provides a basic starting point for any TypeScript project*

The following packages are used as dev-dependencies:

* [eslint](https://www.npmjs.com/package/eslint) - for code linting
* [nodemon](https://www.npmjs.com/package/nodemon) - development server
* [rimraf](https://www.npmjs.com/package/rimraf)  - unix rm -rf for node
* [ts-node](https://www.npmjs.com/package/ts-node) - run ts on node without pre-compiling
* [typescript](https://www.npmjs.com/package/typescript) - TypeScript compiler
* @types/node - TypeScript Definitions
* @typescript-eslint/eslint-plugin - TypeScript Definitions
* @typescript-eslint/parser - TypeScript Definitions

## Table of Contents

* [Overview](#Overview)
* [Installation](#Installation)
* [Usage](#Usage)

## Overview

*Type-starter*, aims to be a starting point for any TypeScript project.  
While some assumptions were made. Not enough to be an opinionated template.  
No testing frameworks have been included and the src and dist folders can be
renamed to lib and build or whatever else may fit your fancy, be sure to change  
the names of the files in all locations.  

## Installation

Navigate tp the repository's homepage and click on `Use this template`.  
And follow the prompts to create the repository.  

Using the terminal, navigate to where you wish to save the project and type the  
following commands, be sure to replace `<USERNAME>` and `<REPO-NAME>`  with the correct information.  

*`HTTPS`*
```sh
git init
git remote add origin https://github.com/<USERNAME>/<REPO-NAME>.git
```  
*`SSH`*  
```sh
git init
git remote add origin git@github.com:<USERNAME>/<REPO-NAME>.git
```

Then  

```sh
git pull origin main
```

## Usage

Scripts have already been added for convenience but can be customized to your needs.  

To run a development server that will watch for changes and hot-reload you can run:  
```sh 
npm run dev 
```  
The other scrips include:  

* start  
```sh
npm start 
or 
npm run start
```  
* build
```sh
npm run build
```  
* lint
```sh
npm run lint
```

## LICENSE

This project is licensed under the [MIT LICENSE](./LICENSE)