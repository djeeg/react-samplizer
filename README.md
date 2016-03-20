React Samplizer
==================================================

There are so many great community React libraries in the ecosystem, however I have found, I can not always get them to work in the same project together.

It is a lot easier for the library maintainers to see my bugs if they have a complete project to get started.

## Setup

```
npm install
npm start
open http://localhost:3000
```

## Test Table

Library | Syntax | Mechanism | Override mechanism | Compile-time step | Media Queries | Pseudo styles | CSS Syntax | Animations | ES6 Classes | Vendor Prefixes | Dynamic styles | Universal/Isomorphic (runs on server)
-------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | --------
[Radium](https://github.com/FormidableLabs/radium) | Plain objects, `{ ':hover': {...}` + `style` attribute + HOC | [Pure inline styles](https://github.com/FormidableLabs/radium#how-does-radium-work) | Object.assign | No | [Yes](https://github.com/FormidableLabs/radium/tree/master/docs/guides#media-queries) | Yes - :hover, :active, :focus | [Yes](https://github.com/FormidableLabs/radium/tree/master/docs/faq#can-i-use-my-favourite-csslesssass-syntax) | [Yes](https://github.com/FormidableLabs/radium/tree/master/docs/api#keyframes) | [Yes](https://github.com/FormidableLabs/radium/tree/master/docs/guides#how-do-i-do-it-then) | Yes | Yes - anything can be done at runtime | Yes, including keyframes and media queries


## Samplized

| Function                              | Current Version           | Discarded  |
| -------------                         |:-------            ------:| -----:|
| view engine                           | React 0.14                |  |
| client routing + lazy loading         | React-Router xxx          |  |
| server render + isomorphic/universal  | React-Router xxx          |  |
| client bundling                       | Webpack 2.0.7             |  |
| client code splitting                 | Webpack 2.0.7             |  |
| client transpiling                    | Babel + Typescript        |  |
| state                                 | Redux                     |  |
| server bundling                       | ts-loader                 |  |
| theme                                 | material-ui               |  |
