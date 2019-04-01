# 💎 Rupi

![npm](https://img.shields.io/badge/npm-next-FF5252.svg)
![build](https://img.shields.io/badge/build-perfect-FF4081.svg)
![coverage](https://img.shields.io/badge/coverage-100-E040FB.svg)
![license](https://img.shields.io/badge/license-MIT-7C4DFF.svg)
![dependencies](https://img.shields.io/badge/dependencies-preact-536DFE.svg)
![performance](https://img.shields.io/badge/performance-blazing-40C4FF.svg)

Rupi is an alternative to Preact with the same syntax, size and functionality.

#### Features: 

- Familiar Preact API
- So incredibly fast
- Everything you need
- Support for hooks
- Support for fragments

## Install

```
$ npm install --save rupi
```

## Usage

```javascript
/** @jsx createElement */

import { createElement, Fragment, render } from "rupi";
import { useEffect } from "rupi/hooks";

function App() {
  useEffect(() => {
    console.log("Component has mounted!");
  }, []);

  return (
    <Fragment>
      <h1>Rupi</h1>
      <p>An alternative to Preact with the same syntax, size and functionality.</p>
    </Fragment>
  );
}

render(<App />, document.querySelector("#root"));
```

## Contribute
1. Clone the repository
2. Run the start script
3. Open a PR with update



