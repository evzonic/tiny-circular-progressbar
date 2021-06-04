# tiny-circular-progressbar

The tiniest circular progress bar

![npm](https://img.shields.io/npm/v/tiny-circular-progressbar)
![npm bundle size](https://img.shields.io/bundlephobia/min/tiny-circular-progressbar)

Creates a tiny circular progress bar.

## Install

```
$ npm install tiny-circular-progressbar
```

## Usage

```js
import React from "react";
import { useEffect } from "react";
import * as CircleProgress from "tiny-circular-progressbar";

useEffect(() => {
  new CircleProgress("progressbar_class_name", {
    max: 100,
    value: 60,
    textFormat: "percent",
  });
}, []);
```
