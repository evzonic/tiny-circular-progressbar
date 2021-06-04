# tiny-circular-progress-bar

The tiniest circular progress bar

![npm (scoped)](https://img.shields.io/npm/v/@evzonic/tiny-circular-progress-bar)
![npm bundle size](https://img.shields.io/bundlephobia/min/@evzonic/tiny-circular-progress-bar)

Creates a tiny circular progress bar.

## Install

```
$ npm install tiny-circular-progress-bar
```

## Usage

```js
import React from "react";
import { useEffect } from "react";
import * as CircleProgress from "tiny-circular-progress-bar";

useEffect(() => {
  new CircleProgress("progress_bar_class_name", {
    max: 100,
    value: 60,
    textFormat: "percent",
  });
}, []);
```
