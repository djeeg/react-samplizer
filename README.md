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

## Samplized

Feature | Mode | Why
-------- | -------- | --------
server code                           | ES6 + Typescript + NodeJS                           | language features, compile time checking, refactoring
client code                           | ES6 + Typescript + Browser                          | language features, compile time checking, refactoring
rendering                             | Isomorphic + Universal                              | pages are refreshable, seo, faster time-to-first-interaction
routing                               | Lazy Loading + Code Splitting                       | smaller initial downloads, faster time-to-first-interaction
bundling                              | Tree Shaking + Chunking                             | smaller downloads, faster time-to-first-interaction

Module | Current Version | Discarded
-------- | -------- | --------
server host                           | express 4.13.4                                      |
server transpiling                    | ts-node 0.5.5 + typescript 1.8.0                    |
server routing                        | react-router 2.0.0                                  |
view engine                           | react 0.14.7                                        |
client transpiling                    | babel 6.4.5 + typescript 1.8.0                      |
client routing                        | react-router 2.0.0                                  |
client bundling                       | webpack 2.0.7-beta                                  |
client code splitting                 | webpack 2.0.7-beta                                  |
state                                 | redux 3.3.1                                         |
immutable                             | immutable 3.7.6                                     |
view connection to state              | react-redux 4.3.0                                   |
route connection to state             | react-router-redux 4.0.0                            |
async                                 | redux-async-connect 1.0.0-rc2 + redux-thunk 1.0.3   |

Library | Current Version | Discarded
-------- | -------- | --------
fetch                                 | isomorphic-fetch 2.2.1 + whatwg-fetch 0.11.0        | , node-fetch 1.3.3, axios 0.9.1
promise                               | es6-promise 3.0.2                                   |

Data | Current Version | Discarded
-------- | -------- | --------
csv parsing                           | csv 0.4.6                                           |

Component | Current Version | Discarded
-------- | -------- | --------
theme                                 | material-ui 0.14.4                                  |
sticky header                         | react-headroom 1.7.3                                |
universal device scroll               | react-iscroll 1.0.0 + iscroll 5.1.3                 |
responsive stream of items            | react-masonry-component 4.0.0                       |
scroll parallax                       | react-parallax 0.3.2                                |
efficient list                        | react-virtualized 5.5.0                             |

Dev | Current Version | Discarded
-------- | -------- | --------
lint                                  | tslint 3.3.0                        |
types                                 | typings 0.7.9                       | tsd
test runner                           | mocha 2.4.4                         |
asserts                               | chai 3.5.0                          |
state audit                           | redux-devtools     3.1.0            |
state replay                          | redux-devtools     3.1.0            |
hot reloading                         | webpack-hot-middleware 2.6.0        | babel-preset-react-hmre 1.0.1, react-transform-hmr 1.0.1
