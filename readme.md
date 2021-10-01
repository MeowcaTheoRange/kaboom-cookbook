# Kaboom CookBook 🍳☕🍩

A place for snippets of Kaboom code

<img width=600px src="https://cms.replit.com/assets/kaboom/blocky.png"></img>

## Components 

* [openClose() - A cyclic animation](https://github.com/marklovers/kaboom-cookbook/tree/main/components/openClose)
* [blink() - Blink your objects](https://github.com/marklovers/kaboom-cookbook/tree/main/components/blink)

## [Kaboom Util](https://github.com/marklovers/kaboom-util)

Kaboom Util is a npm package for import a lot of Kaboom components and plugins in only one import

### Install

NPM: `npm i kaboom-util` <br>
CDN: other day

### Use

```.js
import kaboom from "kaboom";
import kutil from "kaboom-util";

kaboom();

const obj = add([
    rect(4, 4),
    kutil.blink(5)
]);
```
