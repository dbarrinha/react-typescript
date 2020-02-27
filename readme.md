# Criando projeto React + typescript + webpack :rocket:
## Geting stated
##### Creating the project folders
```
mkdir project
cd project
mkdir dist
mkdir src
cd src
mkdir components
```

##### Instaling WebPack dependecies
> npm install --save-dev webpack webpack-cli

##### Instaling React and Typescript dependecies
> npm install --save react react-dom
> npm install --save-dev @types/react @types/react-dom

##### Instaling development-time dependencies
> npm install --save-dev typescript ts-loader source-map-loader

##### Add a TypeScript configuration file
###### Create tsconfig.json file in the root of your project  and paste this:
```
{
    "compilerOptions": {
        "outDir": "./dist/",
        "sourceMap": true,
        "noImplicitAny": true,
        "module": "commonjs",
        "target": "es6",
        "jsx": "react"
    }
}
```

##### Write some code
```
import * as React from "react";

export interface HelloProps { compiler: string; framework: string; }

export const Hello = (props: HelloProps) => <h1>Hello from {props.compiler} and {props.framework}!</h1>;
```

```
{
    "compilerOptions": {
        "outDir": "./dist/",
        "sourceMap": true,
        "noImplicitAny": true,
        "module": "commonjs",
        "target": "es6",
        "jsx": "react"
    }
}
```

```
{
    "compilerOptions": {
        "outDir": "./dist/",
        "sourceMap": true,
        "noImplicitAny": true,
        "module": "commonjs",
        "target": "es6",
        "jsx": "react"
    }
}
```